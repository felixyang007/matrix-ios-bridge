<p align="center">🎉基于usbmuxd的iOS调试工具</p>
<p align="center">
  <a href="https://github.com/felixyang007/matrix-ios-bridge/blob/main/README.md">
    English
  </a>
  <span>| 简体中文</span>
</p>

## 使用方法

#### 1. 下载
[点击这里](https://github.com/felixyang007/matrix-ios-bridge/releases)

#### 2. 执行指令 (windows不需要)
```
sudo chmod 777 ./sib && ./sib version
```

#### 3. 添加sib路径到本机PATH
完成！

## 功能
使用前应该要先mount
```
sib mount
```
然后
```
sib run wda -b your.wda.bundleId
sib run xctest -b your.wda.bundleId
sib remote share
sib remote connect --host 192.168.1.1
sib app list
sib app launch
sib devices listen
sib app uninstall
sib screenshoot
sib ps
sib crash
sib location
sib oritation
sib battery
sib info
...
```

## 感谢

- [https://github.com/electricbubble/gidevice](https://github.com/electricbubble/gidevice)
- [https://github.com/libimobiledevice/libimobiledevice](https://github.com/libimobiledevice/libimobiledevice)
- [https://github.com/danielpaulus/go-ios](https://github.com/danielpaulus/go-ios)

## 开源许可协议

[License](LICENSE)
