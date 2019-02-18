# Docker - Python - Mongo

## Introduction
### A quick and easy way to get Python 3 and Mongo running in a docker compose environment.

## Installation
1. First, make sure you have docker and docker-compose installed on your system
2. `git clone git@github.com:reaperkrew/docker-python-mongo.git`
3. cd into the cloned directory
4. `docker-compose up -d`

## Troubleshooting
If the Mongo build is giving you problems about the `docker-entrypoint.sh`, you probably need to give it executable permissions. Do a `chmod +x docker-entrypoint.sh`. You might need to make a symlink to `/usr/local/bin/docker-entrypoint.sh` also.

Have fun!
