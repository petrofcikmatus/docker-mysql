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

## run

```
docker-compose up -d
```

## connect

```
mysql://db_user:db_pass@mysql:3306/db_name
```

## connect with mysql-client

```
mysql -h mysql -u root -p
```

## use

```sql
DROP TABLE 'users' -- or something productive :)
```

## stop

```bash
docker-compose down
```
