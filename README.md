# A project include follow submoudles:
[1] db - redis and mysql, all users` id cache in redis, and full infomations store in mysql.
[2] userSpider - spider project, created by scrapy.
[3] web-nuxt - a ssr project, manages userinfo, visualizes data.

## Deploy
by docker,
```
git clone this project --recursive
docker-compose build
docker-compose start
```
## db
[1] redis
[2] mysql  

## userSpider 

## web-nuxt
express + nuxt + vue, provide ssr and csr
