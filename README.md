# docker-php

Docker with php include php and cli

## Usage

### Aliyun registry

```shell
docker pull registry.cn-hangzhou.aliyuncs.com/carpedx/php
```

Version included：

- amd64-fpm-7.4-alpine
- amd64-fpm-7.4-bullseye
- amd64-cli-7.4-alpine
- amd64-cli-7.4-bullseye
- arm64-fpm-7.4-alpine
- arm64-fpm-7.4-bullseye  
- arm64-cli-7.4-alpine
- arm64-cli-7.4-bullseye

## Added ext

Detail version see every folder：

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

Most of the content in this file come from [docker-php](https://github.com/yansongda/docker-php)