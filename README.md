# pet

## Dependencies:
 - FastApi
 - Vue
 - Docker
 - Postgres
 - JWT Authentication

 ### Models and Migrations
 - Tortoise for our ORM (Object Relational Mapper) 
 - Aerich for managing database migrations

### commands to update the database
```
docker-compose exec backend aerich migrate
docker-compose exec backend aerich upgrade
```