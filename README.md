# builder.image

These docker files build images that contain build tools.
They are used in building the other docker images in this repository.

### usage
```bash
docker build -t builder:alpine -f Dockerfile.alpine .
docker build -t builder:debian -f Dockerfile.debian .
```
