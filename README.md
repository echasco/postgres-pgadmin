# PostgreSQL and pgAdmin Web with docker-compose 
## Clone repository
```shell
git clone https://github.com/echasco/postgres-pgadmin.git`
```

## Rename .env.example to .env
```shell
mv .env.example .env
```

## Execute docker-compose
```shell
docker-compose up -d`
```

## Open URL
https://localhost:8080

- `User: admin@admin.com`
- `Password: admin`

## Configure postgreSQL connection on PGAdmin
- `Hostname: postgres`
- `Port: 5432`
- `Username: postgres`
- `Password: mysupersecretpassword`

## References
![pgAdmin configuration](https://github.com/echasco/postgres-pgadmin/blob/main/images/image.png)


![pgAdmin connected](https://github.com/echasco/postgres-pgadmin/blob/main/images/image-1.png)