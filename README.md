# SPATesting
Project that implements a .net core 2.1 api and utilises Angular to consume it

## Getting Started
- npm -install in DatingAPP-SPA to get angular dependancies 
- appsettings to modify to modify datasource/jwt token 
- Run dotnet ef update in the api directory to run migrations for the DB, do this after running application atleast one time

## API

- POST <Server>/api/auth/register - username, password body
- POST <Server>/api/auth/login - username, password body | recieve token
- GET <Server>/api/users - Authorization header
- GET <Server>/api/users/{id} - Authorization header

## Prerequisites
Core 2.1, npm, angular6

## Built With
- ASP Core 2.1 - API Framework
- Angular - Client Side Framework
- Bootswatch
- Alertify
- Auth0 - angular-jwt
