## Build image
```
docker build -t lab2.v1 -f Dockerfile5 .
```
## RUN CONTAINERS
```
docker run -d --rm -p 8080:8080 --name lab2 lab2.v1  
```
