# 哄哄 安装包发布

这里只存放「哄哄」安卓安装包（APK）和版本信息，不含源代码。

- 最新版本信息：[`version.json`](version.json)（App 内「检查更新」读取这个文件）
- 历史版本：见 [Releases](../../releases)，每个版本一个标签（如 `v0.1.42`），附 `honghong-<版本>.apk`
- `latest` 发布始终带有最新的 `version.json`

## 安装

1. 在手机上下载对应版本的 `honghong-<版本>.apk`
2. 打开安装，如提示「安装未知应用」，按提示允许后再装
3. 之后 App 会自动提醒新版本，也可以在「我的 → 检查更新」手动检查

`version.json` 里的 `sha256` 可用来校验安装包完整性。
