# FocusApp
一个跨平台同步阅读进度的PDF阅读网站

## 快速开始
如果你的设备有 Docker 环境，可以使用以下命令快速启动一个 Focus 的体验环境：

### 拉取镜像
```shell
docker pull cwghost/focus:latest
```

### 运行
```shell
docker run -d --name focus -p 80:80 -v ~/books:/books cwghost/focus:latest
```
* -p: 端口映射，格式为 `主机(宿主)端口:容器端口`
* -v: 工作目录映射。格式为 `-v 宿主机路径:/books`，后者不能修改

## 默认账户
* 用户名: `admin`
* 密码: `123456`

想了解更多，请查看 [同步进度的多端Pdf 阅读利器 - CSDN](https://blog.csdn.net/m0_37623485/article/details/144269956?spm=1001.2014.3001.5501)
