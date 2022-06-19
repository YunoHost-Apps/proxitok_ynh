<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# ProxiTok for YunoHost

[![Integration level](https://dash.yunohost.org/integration/proxitok.svg)](https://dash.yunohost.org/appci/app/proxitok) ![Working status](https://ci-apps.yunohost.org/ci/badges/proxitok.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/proxitok.maintain.svg)  
[![Install ProxiTok with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=proxitok)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install ProxiTok quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Use Tiktok with an alternative frontend, inspired by Nitter.

### Features

- Privacy: All requests made to TikTok are server-side, so you will never connect to their servers
- See user's feed
- See trending and discovery tab
- See tags
- See video by id
- Themes
- RSS Feed for user, trending and tag (just add /rss to the url)


**Shipped version:** 2.3.1.0~ynh1

**Demo:** https://proxitok.herokuapp.com/

## Screenshots

![Screenshot of ProxiTok](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://proxitok.herokuapp.com>
* Upstream app code repository: <https://github.com/pablouser1/ProxiTok>
* YunoHost documentation for this app: <https://yunohost.org/app_proxitok>
* Report a bug: <https://github.com/YunoHost-Apps/proxitok_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
or
sudo yunohost app upgrade proxitok -u https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
