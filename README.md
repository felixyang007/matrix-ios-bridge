<p align="center">🎉Bridge of iOS Devices by usbmuxd</p>
<p align="center">
  <span>English |</span>
  <a href="https://github.com/felixyang007/matrix-ios-bridge/blob/main/README_CN.md">
     简体中文
  </a>
</p>

## Usage

#### 1. Download
[click here](https://github.com/felixyang007/matrix-ios-bridge/releases)
#### 2. execute shell (No need for windows)
```
sudo chmod 777 ./sib && ./sib version
```
#### 3. Add sib to your PATH
Finish!

## Function
You should mount before use it.
```
sib mount
```
then
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

## Thanks

- [https://github.com/electricbubble/gidevice](https://github.com/electricbubble/gidevice)
- [https://github.com/libimobiledevice/libimobiledevice](https://github.com/libimobiledevice/libimobiledevice)
- [https://github.com/danielpaulus/go-ios](https://github.com/danielpaulus/go-ios)

## LICENSE

[License](LICENSE)
