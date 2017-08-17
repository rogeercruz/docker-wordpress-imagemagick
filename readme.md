# Docker environment to develop wordpress projects with imageMagick
## Content:
  - Wordpress = /php/apache/imagick
  - PhpMyadmin
  - Mysql

By default the WP container will run at port 80
PhpMyadmin will run at 8080 and mysql at 3606
The '.env' file sets the environment variables.

### To run it is necessary install docker.
#### In the terminal type

```
  $ docker-compose build
  $ docker-compose up -d
```
