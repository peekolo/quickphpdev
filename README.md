# Docker container for Quick PHP Dev

A quick container running on php 7.3.2 and apache to spin up for quick php development/testing work.

Mount current directory as entry point of web server, exposed on port 8080.

Build and run docker container (in detached mode):
```
docker-compose up -d
```

You can then access index.php via ```localhost:8080```

Enter container environment:
```
docker exec -it quickphpdev bash
```

Tear down container:
```
docker-compose down
```
