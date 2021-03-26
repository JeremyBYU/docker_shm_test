# Docker Shared Memory Example

All of this code is taken from [here](https://dzone.com/articles/docker-in-action-the-shared-memory-namespace).

The only modification was to create a docker-compose file to integrate everything together (and use host shared memory).

Simply type `docker-compose -f docker-compose.yml up` and you will see the shared memory working between containers.