# Workshop Docker Universitas Wijaya Putra

Percobaan memakai docker compose

# Cara menjalankan

* Install [docker-desktop](https://www.docker.com/products/docker-desktop)
* Jalankan `docker-compose up`. Nanti akan terbentuk folder `database` dan `html`

![docker-compose](docker-compose.png)

# Masuk ke dalam container

Untuk masuk ke dalam container, bisa menjalankan perintah

```sh
# docker exec -it <nama-container> <command>
docker exec -it wordpress_wordpressku_1 /bin/bash
docker exec -it wordpress_mariadbku_1
```