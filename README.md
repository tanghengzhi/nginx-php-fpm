# nginx-php-fpm

Combine the official nginx and php-fpm images

[GitHub](https://github.com/tanghengzhi/nginx-php-fpm)

[Docker Hub](https://hub.docker.com/r/tanghengzhi/nginx-php-fpm/)

# Support Tags

|  Tags   |  Nginx  |  PHP   |
|---------|:-------:|-------:|
| latest  | 1.18.0  | 7.4.14 |
| 7.4     | 1.18.0  | 7.4.14 |
| 8.0     | 1.18.0  | 8.0.1  |

# Build Docker images

docker build -t tanghengzhi/nginx-php-fpm .

docker build -f 7.4/Dockerfile -t tanghengzhi/nginx-php-fpm:7.4

docker build -f 8.0/Dockerfile -t tanghengzhi/nginx-php-fpm:8.0

# Push Docker images to Docker Cloud

docker push tanghengzhi/nginx-php-fpm

docker push tanghengzhi/nginx-php-fpm:7.4

docker push tanghengzhi/nginx-php-fpm:8.0
