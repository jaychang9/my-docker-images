# 构建seata镜像
```shell
docker build --build-arg FILE=seata-server-1.0.0.tar.gz -t harbor.chaomeifan.com/library/seata-server:1.0.0 -f Dockerfile .
docker push harbor.chaomeifan.com/library/seata-server:1.0.0
```



# 构建包含所有字体的openjdk镜像
```shell
docker build -t harbor.chaomeifan.com/library/openjdk:8-jdk-alpine:8-jdk-alpine-v0 -f  Dockerfile .
docker push harbor.chaomeifan.com/library/openjdk:8-jdk-alpine:8-jdk-alpine-v0
···



# 构建包含常用字体的tomcat镜像
```shell
docker build -t harbor.chaomeifan.com/library/tomcat:8.5-jre8-alpine -f Dockerfile .
docker push harbor.chaomeifan.com/library/tomcat:8.5-jre8-alpine
```
