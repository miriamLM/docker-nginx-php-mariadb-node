# docker-nginx-php-mariadb-node

## levantar entorno- Docker compose
- docker-compose up -d --build

## bajar entorno
- docker-compose down

## ejecutar php desde bash
- docker exec -it php-container bash -l

## ejecutar MariaDB desde bash
- docker exec -it mariadb-container bash -l
### abrir mysql
- mysql -h replicasporttipsread.c5qivbkwm4gt.eu-west-1.rds.amazonaws.com -usportread -p
