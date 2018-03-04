# mysql database in docker

## clone

```
git clone git@github.com:petrofcikmatus/mysql.git mysql
```

## add `mysql` to hosts

```
# somewhere in /etc/hosts
127.0.0.1 mysql
```

## build

```
docker-compose build
```

## run

```
docker-compose up -d
```

## connect

```
mysql://db_user:db_pass@mysql:3306/db_name
```

## use

```
DROP TABLE 'users' -- or something productive :)
```

## stop

```
docker-compose down
```
