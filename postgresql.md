---
layout: default
title: PostgreSQL
---

# {{ page.title }}

---

change to postgres user and open psql prompt

`sudo -u postgres psql postgres`



list databases

`postgres=# \l`



list roles

`postgres=# \du`



create role

`postgres=# CREATE ROLE demorole1 WITH LOGIN ENCRYPTED PASSWORD 'password1' CREATEDB;`



alter role

`postgres=# ALTER ROLE demorole1 CREATEROLE CREATEDB REPLICATION SUPERUSER;`



drop role

`postgres=# DROP ROLE demorole1;`



create database

`postgres=# CREATE DATABASE demodb1 WITH OWNER demorole1 ENCODING 'UTF8';`



grant privileges to new user

`GRANT ALL PRIVILEGES ON DATABASE demodb1 TO demorole1;`



drop database

`postgres=# DROP DATABASE demodb1;`



connect to database

`postgres=# \c <databasename>`



list tables in connected database

`postgres=# \dt`



list columns on table

`postgres=# \d <tablename>`



backup database

`pg_dump <databasename> > <outfile>`



import binary sql dump

`pg_restore --create -h localhost -U postgres <infile>`



import txt sql dump

`cat <infile> | psql -U postgres`
