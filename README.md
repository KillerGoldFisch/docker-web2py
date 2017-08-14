# About this repo
The repo contains the Docker image for the [web2py](http://www.web2py.com/) web framework with MySQL. See the hub page. 


```
docker run -d \
    -p 80:80 \
    -p 443:443 \
    -v $PWD/init:/apps/init \
    -e UID=501 \
    --name web2py killergoldfisch/web2py
```