# TICKET - API
Api - Spring boot

## PRE-REQUISITOS
- Java
- Banco de dados Postgres ou 
- Usar banco postgres atraves do Docker | https://docs.docker.com/engine/install/ubuntu/ 

## DOCKER
- RUNNING POSTGRES
- create:
docker run --name ticketlog_db -p 5432:5432 -e POSTGRES_PASSWORD=mysecretpassword -e POSTGRES_DB=ticketlog -d postgres:alpine
- stop:
docker stop postgres
- start:
docker start postgres

## DATABASE DESCRIPTION

|       Estado          |
|--------------------   |
|id: UUID (PK)          |
|name: String           |
|populacao: Long        |
|custoEstadoUs:         |

