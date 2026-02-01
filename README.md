# nginx-controller-repositories-summary

This repository is based in this one: https://github.com/chainguard-forks/ingress-nginx

## How to list builders:
```bash
docker buildx ls
```

### Build nginx base image:
```bash

cd ingress-nginx/images/nginx
make builder
export REGISTRY='andreujove
make build

```

### Build controller image:

```bash

cd ingress-nginx

```
