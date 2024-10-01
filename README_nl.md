<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Redlib voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/redlib.svg)](https://ci-apps.yunohost.org/ci/apps/redlib/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/redlib.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/redlib.maintain.svg)

[![Redlib met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=redlib)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Redlib snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Redlib is an alternative private front-end to Reddit, with its origins in Libreddit. It is a private front-end like Invidious but for Reddit. Browse the coldest takes of r/unpopularopinion without being tracked.

### Features

- Written in Rust for blazing fast speeds and memory safety
- No JavaScript, no ads, no tracking, no bloat
- All requests are proxied through the server, including media
- Strong Content Security Policy prevents browser requests to Reddit


**Geleverde versie:** 0.35.1~ynh5

## Schermafdrukken

![Schermafdrukken van Redlib](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Upstream app codedepot: <https://github.com/redlib-org/redlib>
- YunoHost-store: <https://apps.yunohost.org/app/redlib>
- Meld een bug: <https://github.com/YunoHost-Apps/redlib_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/redlib_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/redlib_ynh/tree/testing --debug
of
sudo yunohost app upgrade redlib -u https://github.com/YunoHost-Apps/redlib_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
