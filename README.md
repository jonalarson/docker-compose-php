# Getting Started

1. Start Docker Desktop 
2. Navigate to the CI directory from the terminal and run `docker-compose` to build and run the container

```bash
cd .ci
docker-compose build .
docker-compose up -d
```

3. Test hot reloading by modifying the `helloworld.php` file.

```bash
curl localhost/helloworld.php
```

## Working with Docker Compose
---

Start/Stop/Restart

```bash
docker-compose up -d
docker-compose down
docker-compose restart webserver
```