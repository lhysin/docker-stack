# Docker Stack

```shell
# kafka cluster and ui
cd kafka

docker-compose -f kafka3-ui-zk1.yml -p kafka3-ui-zk1 up -d
```

```shell
# mariadb and adminer
cd datasource

docker-compose -f mariadb-adminer.yml -p mariadb-adminer up -d
```