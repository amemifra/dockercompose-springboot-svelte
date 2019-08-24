# Docker Compose • Springboot • Svelte | Template
Fullstack template

## Require
This project require:
- [jdk](https://www.oracle.com/technetwork/java/javase/downloads/index.html)
- [maven](https://maven.apache.org/download.cgi)
- [node](https://nodejs.org/it/download/)
- [docker](https://docs.docker.com/)
- [docker-compose](https://docs.docker.com/compose/)

## Run
Open a terminal on project root folder.
Build Frontend:
```
cd Frontend/
npm i
npm run build:java
```
Build Backend:
```
cd Backend/
mvn clean package
```

Build and **run** Docker Compose:
```
docker-compose build
docker-compose up
```