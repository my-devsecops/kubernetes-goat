# Helm Tiller

This docker container is part of Kubernetes Goat.

## Building this docker container

```bash
docker build -t k8sgoat.azurecr.io/helm-tiller .
```

## Push this docker container to Docker Hub

```bash
docker push k8sgoat.azurecr.io/helm-tiller
```

### Reference

* [https://engineering.bitnami.com/articles/helm-security.html](https://engineering.bitnami.com/articles/helm-security.html)

