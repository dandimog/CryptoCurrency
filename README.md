docker build . -t bitcoin:1.0
docker run -p 8080:3000 --name container 2ee5126e98cd