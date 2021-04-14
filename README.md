Symfony5, PHP7.4, PostgresQL with Docker
===

**build project**
```
docker-compose up --build -d
```

**open container**
```
docker exec -it php74-container bash
```

**install Symfony**
```
composer create-project symfony/website-skeleton .
```

**open app in your browser**
```
127.0.0.1:8080
```