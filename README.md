# Metadata Manager

![REPO-TYPE](https://img.shields.io/badge/repo--type-backend-critical?style=for-the-badge&logo=github)

Metadata manager is a helper tool for the Questionnaire Builder that utilizes Postgres (https://www.postgresql.org/), PostgREST (https://github.com/begriffs/postgrest) 
and Swagger UI (https://github.com/swagger-api/swagger-ui) to expose the REST APIs based on the provided database.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

The software can be started up only through Docker and that is the only prerequisite.

## Usage

**Start the containers**

`docker-compose up -d`

**Tearing down the containers**

`docker-compose down --remove-orphans -v`

## Authors

* **Antonino Sirchia** - [sirnino](https://github.com/sirnino) - *Team Lead*
* **Igor Molnar** - [imolnar92](https://github.com/imolnar92) - *Developer*
