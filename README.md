# tix-time-deploy
This repository contains the necessary file to spin-up the whole ingestion and
processing pipeline for the TiX project.

## How to use it
It contains a single Docker Compose file. You only need to configure the
necessary environment variables that are declared but not defined in the file,
and run the command
```
docker-compose up -d
```
