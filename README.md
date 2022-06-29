# My Daily Docker Compose

A list of my frequently used Docker images that I use in my work.

## Table of Contents

+ [Images Included](#images-included)
+ [How to run and stop](#how-to-run-and-stop)

### Images Included

|Image Name|Tag|Is Latest|
|---|---|---|
|redis|latest|Yes|

### How to run and stop

In order to to get all containers running, open a new terminal window and use the following `docker-compose` command:

```powershell
docker-compose up -d
```

This will start a new stack with all the containers running.

To stop and delete the stack, use this command:

```powershell
docker-compose down
```
