# proto
gRPC proto files

## Buf
### Installation
```shell
brew install bufbuild/buf/buf
```
### build
```shell
buf dep update
buf lint
buf build
```
### generate
```shell
buf generate
```
### login
```shell
buf registry login
```
### push
```shell
buf push
```

## Version Control
### git
version format support
- v1.2.0
- v1.3.0-dev.1
- v1.3.0-alpha.1
- v1.3.0-beta.1
- v1.3.0-rc.1
```shell
git tag proto/v1.2.0
git push origin proto/v1.2.0
```
### buf
buf actions: https://github.com/bufbuild/buf-action
```shell
buf push --label v1.2.0
```