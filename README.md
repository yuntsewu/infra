# Infra
One shot personal cloud setup with docker compose.

Dependencies
```
sudo apt update
curl https://get.docker.com | sh # Docker
sudo apt install git docker-compose -y
```
- The server should be exposed to the internet with port 80 and 443 for letsencrypt
- Domain name with a record pointing to the server

Copy sample .env file
```
cp sample.env .env
```
- Edit .env file

docker compose
```
docker-compose up -d --build
```
