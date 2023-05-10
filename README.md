# Kimai2 hosting playground

This repository contains a environment that allows to test [kimai2](https://github.com/kevinpapst/kimai2) deployment.

Ressource: https://hub.docker.com/r/kimai/kimai2

```sh
$ docker compose up -d --wait kamia2
```

```
$ docker compose exec kimai2 /opt/kimai/bin/console kimai:create-user admin admin@example.com ROLE_SUPER_ADMIN password
```

Go to htt://127.0.0.1:8001 

- Login: `admin`
- Password: `password`
