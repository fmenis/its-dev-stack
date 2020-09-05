# its-dev-stack
> Builds the development stack for "Its management System".

## Requirements
- OS: Linux or MacOS (maybe Windows, one day...)
- docker and docker-container
- for Linux users: curl

## Instructions
- download [docker](https://docs.docker.com/engine/install/)
- download [docker-compose](https://docs.docker.com/compose/install/)
- execute init.sh script

## Stack
- postgresql (12.4)
- redis (6)
- portainer (latest)
- pgadmin (4)
- rediscommander (lastest)

### Build and launch containers manually
- docker-compose up -d
- docker-compose down

## Notes
- access postgres via psql --> docker container exec -it postgres psql -U postgres
- access redis via redis-cli --> docker container exec -it redis redis-cli