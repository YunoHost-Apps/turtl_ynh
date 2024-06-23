<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Turtl

[![集成程度](https://dash.yunohost.org/integration/turtl.svg)](https://dash.yunohost.org/appci/app/turtl) ![工作状态](https://ci-apps.yunohost.org/ci/badges/turtl.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/turtl.maintain.svg)

[![使用 YunoHost 安装 Turtl](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=turtl)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Turtl。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Turtl is a free online service that allows you to create, synchronize and find your notes, in an encrypted manner. 

### Features

- Different note types: text, bookmark, password, image, and file/document
- Client-side cryptography to keep all of your data safe
- Securely share with anyone without compromising the security of your data
- Sharing allows different permissions ranging from read-only to full ownership of shared content
- Find your notes easily. Turtl supports full-text search, filtering by tag (or lack of tag), and sort by create/edit date
- Attach photos, files, and documents to your notes. Files are stored securely just like the rest of your data.
- Browser extension makes bookmarking easy on desktop
- Share to Turtl on Android for easy bookmarking and file uploads
- Write notes in Markdown, an easy and natural way to format text
- TeX math expressions in notes for math people (surround them by $$ to use)
- Multiple translations (German, Spanish, French, and more)
- RTL text support for our Farsi/Hebrew/etc-speaking friends
- Export/import your entire profile for backup purposes or to move between servers
- Semi-offline mode (you only need to be connected to log in)
- A number of keyboard shortcuts for navigation the app without mouse (type ? in-app to see shortcuts)
- An open-source server allows you to host your own Turtl data


**分发版本：** 2021.03.05~ynh1

## 截图

![Turtl 的截图](./doc/screenshots/screenshot.png)

## :red_circle: 负面特征

- **Package not maintained**: This YunoHost package is not actively maintained and needs adoption. This means that minimal maintenance is made by volunteers who don't use the app, so you should expect the app to lose reliability over time. You can [learn how to package](https://yunohost.org/packaging_apps_intro) if you'd like to adopt it.

## 文档与资源

- 官方应用网站： <https://turtlapp.com>
- 官方管理文档： <https://turtlapp.com/docs/>
- 上游应用代码库： <https://github.com/turtl/server>
- YunoHost 商店： <https://apps.yunohost.org/app/turtl>
- 报告 bug： <https://github.com/YunoHost-Apps/turtl_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/turtl_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/turtl_ynh/tree/testing --debug
或
sudo yunohost app upgrade turtl -u https://github.com/YunoHost-Apps/turtl_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
