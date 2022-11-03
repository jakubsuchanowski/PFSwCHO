CREATE docker image
docker build -t local/simple-web-app -f Dockerfile5 .

RUN CONTAINERS
docker run -d --rm -p 8080:8080 --name simple-web-app local/simple-web-app
