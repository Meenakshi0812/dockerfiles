### Dockerfiles

Dockerfile is a declarative way of creating our own images. Docker will give us some syntax to create our own images.

File name should be Dockerfile.
### How to build image from Dockerfile

```

docker build -t [dockerhubURL]/[your-username]/[image-name]:version .
```

### How to push image to dockerhub

```
docker push -t [dockerhubURL]/[your-username]/[image-name]:version
```

