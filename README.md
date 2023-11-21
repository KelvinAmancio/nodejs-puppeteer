# NodeJS Puppeteer

This Docker image is based on NodeJS and includes Linux dependencies for Puppeteer and Chromium tools, specifically designed for web scraping.

## Stack

- [Docker](https://www.docker.com/)
- [NodeJS Docker Image](https://hub.docker.com/_/node/)
- [Puppeteer](https://pptr.dev/)

## Running

``` bash
# download image
$ docker pull kelvinbamancio/nodejs-puppeteer

# run container
$ docker run --name nodejs-puppeteer -p 80:8080 -d kelvinbamancio/nodejs-puppeteer

# connect to the container
$ docker exec -it nodejs-puppeteer /bin/sh
```
    

    
