# docker-nginx-npm-yarn
a Docker for Nginx, npm and yarn


## use sample (docker-compose.yml)
```yaml
server2018-web:
  image: marshsu/docker-nginx-npm-yarn
  container_name: server2018-web
  volumes:
    - ./www:/var/www/default
  ports:
    - "19000:80"
 ```


## if you need multiple node version you can see
 - https://thabung.wordpress.com/2017/02/01/install-and-switch-node-js-versions-in-ubuntu/
 - http://nodesource.com/blog/installing-node-js-tutorial-using-nvm-on-mac-os-x-and-ubuntu/


