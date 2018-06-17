Yo world v2! - via nginx
=================


docker build -t nifyworx/yo-world-nginx-v2:latest .
docker run -p 80:80 nifyworx/yo-world-nginx-v2:latest

curl localhost:80 | http://localhost:80
curl localhost:80/v2/ | http://localhost:80/v2/
