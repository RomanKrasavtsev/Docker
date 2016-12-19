# Docker

## MySQL
docker run --name my-mysql -e MYSQL_ROOT_PASSWORD=PASSWORD -d -p 3306:3306 -v ~/Documents/mysql/:/var/lib/mysql/ mysql

## Redis
