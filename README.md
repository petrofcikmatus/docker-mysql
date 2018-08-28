# mysql database in docker

## clone

```
git clone git@github.com:petrofcikmatus/mysql.git mysql
```

## start

```
docker-compose up -d
```

## connect

```
mysql://db_user:db_pass@127.0.0.1:3306/db_name
```

## connect with mysql-client

```
mysql -h 127.0.0.1 -u root -p
```

## use

```sql
DROP TABLE 'users' -- or something more productive :)
```

## stop

```bash
docker-compose down
```
