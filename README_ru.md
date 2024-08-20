<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# ProxiTok для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/proxitok.svg)](https://ci-apps.yunohost.org/ci/apps/proxitok/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/proxitok.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/proxitok.maintain.svg)

[![Установите ProxiTok с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=proxitok)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить ProxiTok быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Use Tiktok with an alternative frontend, inspired by Nitter.

### Features

- Privacy: All requests made to TikTok are server-side, so you will never connect to their servers
- See user's feed
- See trending and discovery tab
- See tags
- See video by id
- Themes
- RSS Feed for user, trending and tag (just add /rss to the url)


**Поставляемая версия:** 2.5.0.0~ynh1

**Демо-версия:** <https://proxitok.herokuapp.com/>

## Снимки экрана

![Снимок экрана ProxiTok](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://proxitok.herokuapp.com>
- Репозиторий кода главной ветки приложения: <https://github.com/pablouser1/ProxiTok>
- Магазин YunoHost: <https://apps.yunohost.org/app/proxitok>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/proxitok_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
или
sudo yunohost app upgrade proxitok -u https://github.com/YunoHost-Apps/proxitok_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
