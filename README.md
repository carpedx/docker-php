# docker-php

Docker with php include php and cli

## Usage

### Aliyun registry
docker pull registry.cn-hangzhou.aliyuncs.com/carpedx/php

- 7.4

## Added ext

detail version see every floder

- amqp
- bcmath
- bz2 
- gd 
- iconv 
- mcrypt
- mysqli
- pdo
- pdo_mysql
- zip
- mongodb
- redis
- memcached
- swoole
- opcache
- sockets

## Modified php.ini

- memory_limit = 512M
- post_max_size = 64M
- upload_max_filesize = 32M
- date.timezone = Asia/Shanghai
- max_execution_time = 60

## Added tools

- composer

## License

MIT

Most of the methods in this file come from [docker-php](https://github.com/yansongda/docker-php)