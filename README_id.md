<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# ProxiTok untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/proxitok.svg)](https://ci-apps.yunohost.org/ci/apps/proxitok/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/proxitok.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/proxitok.maintain.svg)

[![Pasang ProxiTok dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=proxitok)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang ProxiTok secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Use Tiktok with an alternative frontend, inspired by Nitter.

### Features

- Privacy: All requests made to TikTok are server-side, so you will never connect to their servers
- See user's feed
- See trending and discovery tab
- See tags
- See video by id
- Themes
- RSS Feed for user, trending and tag (just add /rss to the url)


**Versi terkirim:** 2.5.0.0~ynh1

**Demo:** <https://proxitok.herokuapp.com/>

## Tangkapan Layar

![Tangkapan Layar pada ProxiTok](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://proxitok.herokuapp.com>
- Depot kode aplikasi hulu: <https://github.com/pablouser1/ProxiTok>
- Gudang YunoHost: <https://apps.yunohost.org/app/proxitok>
- Laporkan bug: <https://github.com/YunoHost-Apps/proxitok_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
atau
sudo yunohost app upgrade proxitok -u https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
