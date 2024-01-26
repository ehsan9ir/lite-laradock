# laradock-lite

A Docker based laravel development environment with minimal dependencies.

Fork: [laradock](https://github.com/laradock/laradock)


## Quick Overview[#](https://laradock.io/introduction/#quick-overview "Permanent link")

Let’s see how easy it is to setup our demo stack  `PHP`,  `NGINX`,  `MySQL`,  `Redis`  and  `Composer`:

1 - Enter the laradock folder and rename  `.env.example`  to  `.env`.

```shell
cp .env.example .env

```

2 - Run your containers:

```shell
docker-compose up -d nginx mysql phpmyadmin redis workspace 

```

3 - Open your project’s  `.env`  file and set the following:

```shell
DB_HOST=mysql
REDIS_HOST=redis
QUEUE_HOST=beanstalkd

```

4 - Open your browser and visit localhost:  `http://localhost`.

```shell
That's it! enjoy :)
```

## License

[MIT](https://github.com/laradock/laradock/blob/master/LICENSE) © Mahmoud Zalt
