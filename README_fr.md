# ProxiTok pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/proxitok.svg)](https://dash.yunohost.org/appci/app/proxitok) ![](https://ci-apps.yunohost.org/ci/badges/proxitok.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/proxitok.maintain.svg)  
[![Installer ProxiTok avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=proxitok)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer ProxiTok rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Use Tiktok with an alternative frontend, inspired by Nitter.

### Features

    Privacy: All requests made to TikTok are server-side, so you will never connect to their servers
    See user's feed
    See trending and discovery tab
    See tags
    See video by id
    Themes
    RSS Feed for user, trending and tag (just add /rss to the url)


**Version incluse :** 2.2.0.0~ynh1

**Démo :** https://demo.example.com

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?

## Documentations et ressources

* Site officiel de l'app : proxitok.herokuapp.com
* Documentation officielle utilisateur : https://yunohost.org/apps
* Documentation officielle de l'admin : https://yunohost.org/packaging_apps
* Dépôt de code officiel de l'app : https://github.com/pablouser1/ProxiTok
* Documentation YunoHost pour cette app : https://yunohost.org/app_proxitok
* Signaler un bug : https://github.com/YunoHost-Apps/proxitok_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
ou
sudo yunohost app upgrade proxitok -u https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps