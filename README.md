# Greenlight

![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)

Greenlight is a movies API for storing and accessing information about movies. The project comes from the book [Let's Go Further](https://lets-go-further.alexedwards.net/) by Alex Edwards.

## Endpoints

|Method|URL|Action|
|------|---|------|
|GET|/v1/healthcheck|Check if the API is available|
|GET|/v1/movies|Get list of movies|
|POST|/v1/movies|Create new movie|
|GET|/v1/movies/:id|Get movie from ID|
|PATCH|/v1/movies/:id|Update movie from ID|
|DELETE|/v1/movies/:id|Delete movie from ID|
|POST|/v1/users|Create new user|
|PUT|/v1/users/activated|Activate user|
|POST|/v1/tokens/authentication|Create authentication token for use|

# Features

 - CRUD methods
 - REST API
 - SQL migrations
 - Filtering, sorting, and pagination
 - Authentication
   - Create user
   - Email verification
   - Token authentication
 - Partial updates
 - Security
   - Hashed passwords
   - Rate limiter
   - Graceful shutdown
 - Metrics
