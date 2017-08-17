## Docker environment to develop wordpress projects with imageMagick
#### This environment contains:
  - Wordpress = /php/apache/imagick
  - PhpMyadmin
  - Mysql

By default the WordPress container will run at port 80 (is possible to change this inside docker-compose.yml),
phpMyAdmin will run at 8080 and mysql at 3606
The '.env' file sets the environment variables.

#### To run it is necessary to install [docker!](https://www.docker.com/)
#### In the terminal type

```
  $ docker-compose build
  $ docker-compose up -d
```
