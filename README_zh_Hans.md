<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Anubis

[![集成程度](https://apps.yunohost.org/badge/integration/anubis)](https://ci-apps.yunohost.org/ci/apps/anubis/)
![工作状态](https://apps.yunohost.org/badge/state/anubis)
![维护状态](https://apps.yunohost.org/badge/maintained/anubis)

[![使用 YunoHost 安装 Anubis](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=anubis)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Anubis。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Anubis weighs the soul of your connection using a sha256 proof-of-work challenge in order to protect upstream resources from scraper bots.
This program is designed to help protect the small internet from the endless storm of requests that flood in from AI companies. Anubis is as lightweight as possible to ensure that everyone can afford to protect the communities closest to them.
Anubis is a bit of a nuclear response. This will result in your website being blocked from smaller scrapers and may inhibit "good bots" like the Internet Archive. You can configure bot policy definitions to explicitly allowlist them and we are working on a curated set of "known good" bots to allow for a compromise between discoverability and uptime.


**分发版本：** 1.14.2.~ynh1

## 截图

![Anubis 的截图](./doc/screenshots/example.jpg)

## 文档与资源

- 官方应用网站： <https://anubis.techaro.lol/>
- 官方管理文档： <https://anubis.techaro.lol/docs/admin/installation>
- 上游应用代码库： <https://github.com/TecharoHQ/anubis>
- YunoHost 商店： <https://apps.yunohost.org/app/anubis>
- 报告 bug： <https://github.com/YunoHost-Apps/anubis_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/anubis_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/anubis_ynh/tree/testing --debug
或
sudo yunohost app upgrade anubis -u https://github.com/YunoHost-Apps/anubis_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
