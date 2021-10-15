
# How to run with Docker

## Build Docker Image for reviews service
```
docker build -t reviews .
```
## Run ratings service on port 8082
```
docker run -d --name reviews -p 8082:9080 reviews
```
* Test with path `/ratings/1` and `/health`