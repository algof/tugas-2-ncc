# Cara akses database

```sh
cat ~/CTFd/docker-compose.yml
```

Cari bagian `db`

Cari `MARIADB_USER` dan `MARIADB_PASSWORD`

```sh
sudo docker ps
```

Cari kontainer mariadb

```sh
sudo docker exec -it <nama-container> mysql -u <mariadb-user> -p
```

sudo ```sh
docker exec -it ctfd-db-1 mysql -u ctfd -p
```

Saat muncul `Enter password:` isi `ctfd`