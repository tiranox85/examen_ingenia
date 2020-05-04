# Fernqndo gil Symfony basic crud

Para correr el proyecto:
```
cd docker

docker-compose up -d
```

## Composer install 
```
docker-compose run php-fpm composer install
```

### Database (MariaDB)
```
docker-compose run php-fpm bin/console doctrine:migrations:migrate  
```

La canfiguración de la DB se encuentra en el archivo .env