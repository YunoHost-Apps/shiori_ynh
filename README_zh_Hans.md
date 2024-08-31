<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Shiori

[![集成程度](https://dash.yunohost.org/integration/shiori.svg)](https://ci-apps.yunohost.org/ci/apps/shiori/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/shiori.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/shiori.maintain.svg)

[![使用 YunoHost 安装 Shiori](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shiori)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Shiori。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Shiori is a simple bookmarks manager written in Go language. Intended as a simple clone of Pocket. You can use it as command line application or as web application. This application is distributed as a single binary, which means it can be installed and used easily.

### Features

- Simple and clean command line interface.
- Basic bookmarks management i.e. add, edit and delete.
- Search bookmarks by their title, tags, URL and page content.
- Import and export bookmarks from and to Netscape Bookmark file.
- Simple web interface for those who don't want to use a command line app.
- Where possible, by default shiori will download a static copy of the webpage in simple text and HTML format, which later can be used as an offline archive for that page.


**分发版本：** 1.7.0~ynh3

## 截图

![Shiori 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方用户文档： <https://github.com/go-shiori/shiori/wiki/Usage>
- 官方管理文档： <https://github.com/go-shiori/shiori/wiki>
- 上游应用代码库： <https://github.com/go-shiori/shiori>
- YunoHost 商店： <https://apps.yunohost.org/app/shiori>
- 报告 bug： <https://github.com/YunoHost-Apps/shiori_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/shiori_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
或
sudo yunohost app upgrade shiori -u https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
