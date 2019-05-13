# nginx-php-fpm

Combine the official nginx and php-fpm images

[GitHub](https://github.com/tanghengzhi/nginx-php-fpm)

[Docker Hub](https://hub.docker.com/r/tanghengzhi/nginx-php-fpm/)

# Support Tags

|  Tags   |  Nginx  |  PHP   |
|---------|:-------:|-------:|
| latest  | 1.14.2  | 7.3.5  |
| 7.3     | 1.14.2  | 7.3.5  |
| 7.2     | 1.14.2  | 7.2.18 |

# Build Docker images

docker build -t tanghengzhi/nginx-php-fpm .

docker build -f 7.3/Dockerfile -t tanghengzhi/nginx-php-fpm:7.3

docker build -f 7.2/Dockerfile -t tanghengzhi/nginx-php-fpm:7.2

# Push Docker images to Docker Cloud

docker push tanghengzhi/nginx-php-fpm

docker push tanghengzhi/nginx-php-fpm:7.3

docker push tanghengzhi/nginx-php-fpm:7.2
