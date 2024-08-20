<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# ProxiTok pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/proxitok.svg)](https://ci-apps.yunohost.org/ci/apps/proxitok/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/proxitok.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/proxitok.maintain.svg)

[![Installer ProxiTok avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=proxitok)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer ProxiTok rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

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


**Version incluse :** 2.5.0.0~ynh1

**Démo :** <https://proxitok.herokuapp.com/>

## Captures d’écran

![Capture d’écran de ProxiTok](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://proxitok.herokuapp.com>
- Dépôt de code officiel de l’app : <https://github.com/pablouser1/ProxiTok>
- YunoHost Store : <https://apps.yunohost.org/app/proxitok>
- Signaler un bug : <https://github.com/YunoHost-Apps/proxitok_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
ou
sudo yunohost app upgrade proxitok -u https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
