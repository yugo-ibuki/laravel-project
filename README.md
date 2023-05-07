https://www.kamome-susume.com/laravel-docker/

- laravel 8
- mysql 8
- node 16
- phpmyadmin

# start

```bash
cp ./.env.sample ./.env
cp ./src/.env.sample ./src/.env
```

```bash
docker exec  -it laravel_todo_php bash
```

```bash
root@ce92cbdbc390:/var/www# php artisan key:generate
```
