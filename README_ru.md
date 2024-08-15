<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Libreddit для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/libreddit.svg)](https://ci-apps.yunohost.org/ci/apps/libreddit/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/libreddit.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/libreddit.maintain.svg)

[![Установите Libreddit с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=libreddit)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Libreddit быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Libreddit is a portmanteau of "libre" (meaning freedom) and "Reddit". It is a private front-end like Invidious but for Reddit. Browse the coldest takes of r/unpopularopinion without being tracked.

### Features

- Written in Rust for blazing fast speeds and memory safety
- No JavaScript, no ads, no tracking, no bloat
- All requests are proxied through the server, including media
- Strong Content Security Policy prevents browser requests to Reddit


**Поставляемая версия:** 0.35.1~ynh2

**Демо-версия:** <https://libreddit.spike.codes/>

## Снимки экрана

![Снимок экрана Libreddit](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://libreddit.spike.codes/>
- Репозиторий кода главной ветки приложения: <https://github.com/spikecodes/libreddit>
- Магазин YunoHost: <https://apps.yunohost.org/app/libreddit>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/libreddit_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
или
sudo yunohost app upgrade libreddit -u https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
