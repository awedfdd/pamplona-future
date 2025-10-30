# Pamplona Future
### An open-source private server implementation for Mirror's Edge™: Catalyst.
## Setup
### Requirements
- wsl2
- git, docker, docker compose

### Connecting
Drop `dinput8.dll` and `EA-MITM.ini` into your game folder

### Deploying via Docker
`docker compose up -d --build` to run from the root of the project.

Logs can be displayed by using `docker logs -f pamplona-future`. To stop the server and database containers, run `docker compose down`.
