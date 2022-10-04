# Ubuntu for go

To build this image run this command and replace <version> with the go version:

```shell
docker build --build-arg GO_VERSION=<version> -t ubuntu-go .
```