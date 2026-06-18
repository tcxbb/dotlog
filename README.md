# Dotlog

Dotlog 是一个极简的个人时间打点工具。

## 使用方式

- 打开 `index.html` 可以在本地浏览器直接使用。
- 在设置页填写 GitHub Token 和 Gist ID 后，可以通过 GitHub Gist 在多设备之间同步数据。
- 部署到 GitHub Pages 后，可以在手机 Safari 中添加到主屏幕，像 App 一样打开。

## 数据同步

同步数据保存在 Gist 文件 `dotlog_data.json` 中。本地 `localStorage` 会作为缓存，离线时仍可查看和记录，恢复网络后再次同步。

## GitHub Pages 地址

部署后访问：

https://tcxbb.github.io/dotlog/
