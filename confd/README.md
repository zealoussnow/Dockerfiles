## Build镜像

```
docker build -t golang-1.11.13-buster-aarch64 .
```

## 运行编译confd的容器

```
docker run -v <COFD_DIR>:/app golang-1.11.13-buster-aarch64 -it sh
```

## 进入到docker中后，直接执行make即可
