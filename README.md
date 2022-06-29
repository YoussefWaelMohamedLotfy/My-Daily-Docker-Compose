# My Daily Docker Compose

A list of my frequently used Docker images that I use in my work.

## Table of Contents

+ [How to run and stop](#how-to-run-and-stop)
+ [Images Included](#images-included)
+ [Note on images](#notes-on-images)

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

### Images Included

|Image Name|Tag|Is Latest|
|---|:---:|:---:|
|redis|latest|Yes|
|mcr.microsoft.com/mssql/server|2019-latest|Yes|
|mongo|latest|Yes|
|rabbitmq|management|Yes|
|portainer/portainer-ce|latest|Yes|
|datalust/seq|latest|Yes|
|docker.elastic.co/elasticsearch/elasticsearch|7.17.5|No|
|docker.elastic.co/kibana/kibana|7.17.5|No|
|docker.elastic.co/apm/apm-server|7.17.5|No|

### Notes on images
