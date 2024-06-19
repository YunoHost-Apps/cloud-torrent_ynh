<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Cloud Torrent

[![集成程度](https://dash.yunohost.org/integration/cloud-torrent.svg)](https://dash.yunohost.org/appci/app/cloud-torrent) ![工作状态](https://ci-apps.yunohost.org/ci/badges/cloud-torrent.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/cloud-torrent.maintain.svg)

[![使用 YunoHost 安装 Cloud Torrent](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cloud-torrent)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Cloud Torrent。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Cloud-Torrent is a a self-hosted remote torrent client, written in Go (golang). Started torrents remotely, download sets of files on the local disk of the server, which are then retrievable or streamable via HTTP.

### Features

- Individual file download control (1.1.3+)
- Run external program on tasks completion
- Stops task when seeding ratio reached
- Download/Upload speed limiter
- Detailed transfer stats in web UI.
- Torrent Watcher
- Extra trackers from external source
- Protocol Handler to magnet
- Magnet RSS subscribing supported


**分发版本：** 0.9.1~ynh1

## 截图

![Cloud Torrent 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方管理文档： <https://github.com/jpillora/cloud-torrent/wiki/>
- 上游应用代码库： <https://github.com/jpillora/cloud-torrent>
- YunoHost 商店： <https://apps.yunohost.org/app/cloud-torrent>
- 报告 bug： <https://github.com/YunoHost-Apps/cloud-torrent_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/cloud-torrent_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cloud-torrent_ynh/tree/testing --debug
或
sudo yunohost app upgrade cloud-torrent -u https://github.com/YunoHost-Apps/cloud-torrent_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
