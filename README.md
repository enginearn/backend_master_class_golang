# Backend master class

## docker commands

``` Powershell
> docker run --name postgres15 -p 54320:5432 -e POSTGRES_USER=root -e POSTGRES_PASSWORD=secret -d postgres:latest
> docker exec -it postgres15 psql -U root
sql (15.2 (Debian 15.2-1.pgdg110+1))
Type "help" for help.

root=#
```
