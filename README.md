# docker-cocoapods

Build context for a CocoaPods docker container.

[https://cocoapods.org](https://cocoapods.org)

### Use image from registry

```
docker run --rm -v `pwd`:/project -w /project arguiot/cocoapods:latest pod init
```

### Build image

```
./build-image.sh
```
