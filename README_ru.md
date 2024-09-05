<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Redlib для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/redlib.svg)](https://ci-apps.yunohost.org/ci/apps/redlib/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/redlib.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/redlib.maintain.svg)

[![Установите Redlib с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=redlib)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Redlib быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Redlib is an alternative private front-end to Reddit, with its origins in Libreddit. It is a private front-end like Invidious but for Reddit. Browse the coldest takes of r/unpopularopinion without being tracked.

### Features

- Written in Rust for blazing fast speeds and memory safety
- No JavaScript, no ads, no tracking, no bloat
- All requests are proxied through the server, including media
- Strong Content Security Policy prevents browser requests to Reddit


**Поставляемая версия:** 0.35.1~ynh3

## Снимки экрана

![Снимок экрана Redlib](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Репозиторий кода главной ветки приложения: <https://github.com/redlib-org/redlib>
- Магазин YunoHost: <https://apps.yunohost.org/app/redlib>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/redlib_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/redlib_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/redlib_ynh/tree/testing --debug
или
sudo yunohost app upgrade redlib -u https://github.com/YunoHost-Apps/redlib_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
