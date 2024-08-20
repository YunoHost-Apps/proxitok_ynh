<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# ProxiTok YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/proxitok.svg)](https://ci-apps.yunohost.org/ci/apps/proxitok/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/proxitok.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/proxitok.maintain.svg)

[![Instalatu ProxiTok YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=proxitok)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek ProxiTok YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Use Tiktok with an alternative frontend, inspired by Nitter.

### Features

- Privacy: All requests made to TikTok are server-side, so you will never connect to their servers
- See user's feed
- See trending and discovery tab
- See tags
- See video by id
- Themes
- RSS Feed for user, trending and tag (just add /rss to the url)


**Paketatutako bertsioa:** 2.5.0.0~ynh1

**Demoa:** <https://proxitok.herokuapp.com/>

## Pantaila-argazkiak

![ProxiTok(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://proxitok.herokuapp.com>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/pablouser1/ProxiTok>
- YunoHost Denda: <https://apps.yunohost.org/app/proxitok>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/proxitok_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
edo
sudo yunohost app upgrade proxitok -u https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
