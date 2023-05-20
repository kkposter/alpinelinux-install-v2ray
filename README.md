# alpinelinux-install-v2ray
支持v2ray的5.0以上版本的安装

## 依赖

### 安裝 cURL

```
# apk add curl
```

## 下载

```
$ curl -O https://raw.githubusercontent.com/kkposter/alpinelinux-install-v2ray/master/install-release.sh
```

## 使用

不加参数则下载最新版本
```
# ash install-release.sh 版本
```
示例：
```
# ash install-release.sh 5.1.0
```


## 管理指令

### 启用

```
# rc-update add v2ray
```

### 禁用

```
# rc-update del v2ray
```

### 启动

```
# rc-service v2ray start
```

### 关闭

```
# rc-service v2ray stop
```

### 重启

```
# rc-service v2ray restart
```
