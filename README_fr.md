<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# ProxiTok pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/proxitok.svg)](https://dash.yunohost.org/appci/app/proxitok) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/proxitok.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/proxitok.maintain.svg)

[![Installer ProxiTok avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=proxitok)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d’installer ProxiTok rapidement et simplement sur un serveur YunoHost.
Si vous n’avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Use Tiktok with an alternative frontend, inspired by Nitter.

### Features

- Privacy: All requests made to TikTok are server-side, so you will never connect to their servers
- See user's feed
- See trending and discovery tab
- See tags
- See video by id
- Themes
- RSS Feed for user, trending and tag (just add /rss to the url)


**Version incluse :** 2.4.9.2~ynh1

**Démo :** https://proxitok.herokuapp.com/

## Captures d’écran

![Capture d’écran de ProxiTok](./doc/screenshots/screenshot.png)

## Documentations et ressources

* Site officiel de l’app : <https://proxitok.herokuapp.com>
* Dépôt de code officiel de l’app : <https://github.com/pablouser1/ProxiTok>
* Documentation YunoHost pour cette app : <https://yunohost.org/app_proxitok>
* Signaler un bug : <https://github.com/YunoHost-Apps/proxitok_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
ou
sudo yunohost app upgrade proxitok -u https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>