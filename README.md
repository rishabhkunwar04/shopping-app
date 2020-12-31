<h1 align="center"> SHOPPING -APP</h1>

## DataBase setup
```
create database shopdb;

create user shopuser identified with mysql_native_password by 'shoppass';

grant all privileges on shopdb.*  to shopuser;

flush privileges;


```