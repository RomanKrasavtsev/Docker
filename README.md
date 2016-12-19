# Docker

## MySQL
```
docker run --name my-mysql -e MYSQL_ROOT_PASSWORD=$PASSWORD -d -p 3306:3306 -v ~/Documents/mysql/:/var/lib/mysql/ mysql
docker stop $ID
cp -R /usr/local/mysql/data/DATABASE ~/Documents/mysql
docker start $ID
```

## Redis
```
docker run --name vashkontrol-redis -d -p 6379:6379 -v ~/Documents/redis/:/data/ redis
docker stop $ID
cp 
docker start $ID
```
