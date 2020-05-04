# Fernando Gil Symfony basic crud

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

La configuración de la DB se encuentra en el archivo .env

Este repositorio usa Validation de symfony https://symfony.com/doc/current/validation.html
```    
src/config/packages/framework.yaml
```
