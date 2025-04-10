Kræver at docker er installeret
https://docs.docker.com/engine/install/

# For at køre
Gå ind i server mappe
skriv:
docker-compose up --build -d
i terminalen

Efter dette vil i kunne køre server ved at skrive
docker-compose up


Caddy sørger for certificat

Grunden til at den i starten siger ikke sikker er fordi der er specificeret localhost i Caddyfile.
Hvis dette var et rigtigt domæne ville det ikke være et problem

# Documentation
## Caddy
https://caddyserver.com/docs/

## Docker
https://docs.docker.com/get-started/

### Docker Compose
https://docs.docker.com/compose/


