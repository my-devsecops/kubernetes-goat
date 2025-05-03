# Build Code

This docker container is part of Kubernetes Goat.

## Building this docker container

```bash
docker build -t k8sgoat.azurecr.io/build-code .
```

## Push this docker container to Docker Hub

```bash
docker push k8sgoat.azurecr.io/build-code
```

## Extra

* Build the `app` binary for the linux using the following command

```bash
GOOS=linux GOARCH=amd64 CGO_ENABLED=0 go build
```
