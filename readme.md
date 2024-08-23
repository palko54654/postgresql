1. docker compose up -d
2. go to localhost:5050
3. login by .env credentials
4. check for ip: docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' postgresql
5. create server by credentials with ip of what u get from 4.
