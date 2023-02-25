# Jenkins with CASC for Training Purposes

## Requrements
1. Docker >= 23
2. Internet connection :)

## Components
* Docker `jdk17` agent based on `docker-inbound` image.
* `maven-3.9.0` tool
* mounts `/var/run/docker.sock` to use Docker Agents

## Usage
1. Build Jenkins and Run
```bash
docker compose build
docker compose up -d
```
2. Open Jenkins in WebBrowser http://localhost:8099