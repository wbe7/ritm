## Build

```bash
docker buildx build --platform linux/amd64,linux/arm64 --push -t wbe7/ritm:v1.0 .
```

## Deploy

```bash
kubectl apply -f deploy/
```

## Test

```bash
curl -v https://ritm.cloudnative.space/docs
```