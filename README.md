# 构建工具

不再使用 BlueBuild Template &nbsp;

[![bluebuild build badge](https://github.com/blue-build/template/actions/workflows/build.yml/badge.svg)](https://github.com/blue-build/template/actions/workflows/build.yml)

转而使用 bootc

# 基座

quay.io/centos-bootc/centos-bootc:stream10 的具体软件配置文件不知道在哪。

```
podman run --rm quay.io/centos-bootc/centos-bootc:stream10 rpm -qa | sort 
```
```
podman rmi quay.io/centos-bootc/centos-bootc:stream10
```

# 构建产物

(1) OCI镜像

