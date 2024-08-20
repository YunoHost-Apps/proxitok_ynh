<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 ProxiTok

[![集成程度](https://dash.yunohost.org/integration/proxitok.svg)](https://ci-apps.yunohost.org/ci/apps/proxitok/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/proxitok.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/proxitok.maintain.svg)

[![使用 YunoHost 安装 ProxiTok](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=proxitok)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 ProxiTok。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Use Tiktok with an alternative frontend, inspired by Nitter.

### Features

- Privacy: All requests made to TikTok are server-side, so you will never connect to their servers
- See user's feed
- See trending and discovery tab
- See tags
- See video by id
- Themes
- RSS Feed for user, trending and tag (just add /rss to the url)


**分发版本：** 2.5.0.0~ynh1

**演示：** <https://proxitok.herokuapp.com/>

## 截图

![ProxiTok 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://proxitok.herokuapp.com>
- 上游应用代码库： <https://github.com/pablouser1/ProxiTok>
- YunoHost 商店： <https://apps.yunohost.org/app/proxitok>
- 报告 bug： <https://github.com/YunoHost-Apps/proxitok_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
或
sudo yunohost app upgrade proxitok -u https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
