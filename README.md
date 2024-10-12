# postgres-pgadmin web with docker-compose 
## Clone repository
- `git clone https://github.com/echasco/postgres-pgadmin.git`

## Rename .env.example to .env
- `mv .env.example .env`

## Execute docker-compose
- `docker-compose up -d`

## Open URL
https://localhost:8080

- `User: admin@admin.com`
- `Password: admin`

## Configure postgreSQL connection on PGAdmin
- `Hostname: postgres`
- `Port: 5432`
- `Username: postgres`
- `Password: mysupersecretpassword`