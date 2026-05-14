# Auto.js APK Source Viewer

![Android](https://img.shields.io/badge/Android-APK-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Auto.js](https://img.shields.io/badge/Auto.js-Source%20Viewer-1f8a70?style=for-the-badge)
![Release](https://img.shields.io/badge/Release-Signed%20APK-blue?style=for-the-badge)

一个面向 Auto.js APK 的源码明文查看工具。

它把 APK 分析、源码明文展示、复制、保存和关键数据整理放到一个移动端应用里，适合在手机上快速查看打包后的 Auto.js 项目内容，也适合用作逆向学习和 APK 结构分析的演示案例。

## 下载

- [下载工具安装包](apks/source-viewer-signed.apk)
- [下载案例 APK](apks/sample-autojs.apk)
- [查看 SHA256 校验](checksums/SHA256SUMS.txt)

## 项目亮点

- 一键选择 APK，自动识别 Auto.js 项目结构
- 自动读取 `project.json`、主脚本、包名、版本和构建信息
- 支持源码明文展示，可直接复制 JS 内容
- 支持保存恢复出的 `main.recovered.js`
- 自动提取字符串、URL、接口地址和关键配置
- 内置案例 APK，方便快速测试完整流程
- Android 端直接使用，不需要电脑端 exe

## 仓库内容

```text
apks/
  sample-autojs.apk          案例 Auto.js APK
  source-viewer-signed.apk   已签名 Android 安装包

checksums/
  SHA256SUMS.txt             文件校验值
```

## 使用方式

1. 下载 `apks/source-viewer-signed.apk`
2. 安装到 Android 手机
3. 打开应用，选择需要分析的 APK
4. 进入“源码”页查看 JS 明文
5. 使用“复制 JS 明文”或“保存源码明文”导出结果

## 案例说明

仓库内置 `sample-autojs.apk` 作为演示案例。安装工具后选择该 APK，即可看到项目配置、字符串、URL 和源码明文结果。

## 文件校验

下载后可以使用 `checksums/SHA256SUMS.txt` 校验文件完整性。

## 作者

由 [@xqzfd1](https://github.com/xqzfd1) 制作和维护。

专注 Auto.js、Android APK 分析和移动端工具化，把复杂流程做成可以直接上手的应用。

如果这个项目对你有帮助，欢迎 Star、Fork，也欢迎提交建议，让这个工具变得更顺手。
