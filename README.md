# PostgreSQL Database Health Report

A small Python project that generates a basic health report for a PostgreSQL database.

The script connects to a database in PostgreSQL and runs SQL queries to analyze database.

## Features

- checks number of active connections and max connections
- reports database size
- lists all tables by size
- displays the server start time and calculates its uptime 

## Tech stack

- Python
- PostgreSQL
- SQL
- psycopg

## Example output

## 1
Database health report
------------------------ 

Number of connections on database pg4e_3fb3abd7f7 is 26.
Maximal connections allowed: 200.
------------------------------------------------------------------------
Size of database is: 8797 kB
------------------------------------------------------------------------
Tables ordered by size in database pg4e_3fb3abd7f7:

tickets 96 kB
track_raw 64 kB
car_make 48 kB
car_model 48 kB
pg4e_meta 48 kB
course 40 kB
make 40 kB
roster 40 kB
student 40 kB
pg4e_debug 32 kB
pg4e_result 32 kB
automagic 24 kB
model 24 kB
car 24 kB
ages 8192 bytes
------------------------------------------------------------------------
Server last started on: 23.05.2025 14:47:56
------------------------------------------------------------------------
Server is up for: 289 days 21:45:00
Selection deleted




## 2

Database health report
------------------------ 

Database name: pg4e_3fb3abd7f7
Database size: 8797 kB
Number of connections: 27
Max connections: 200
Server started on: 23.05.2025 14:47:56
Server uptime: 289 days 21:45:07