# alpinelinux-install-xray

English | [中文(中国)](README_zh-cn.md) | [中文(薹灣)](README_zh-tw.md)

## Install dependencies

### Install cURL

```
# apk add curl
```

## Download

```
$ curl -O https://raw.githubusercontent.com/wimdaw/alpine-install-xray/main/install-release.sh
```

## Use

```
# ash install-release.sh
```

## Commands

### Enable

```
# rc-update add xray
```

### Disable

```
# rc-update del xray
```

### Start

```
# rc-service xray start
```

### Stop

```
# rc-service xray stop
```

### Restart

```
# rc-service xray restart
```
