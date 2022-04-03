# Libreddit pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/libreddit.svg)](https://dash.yunohost.org/appci/app/libreddit) ![](https://ci-apps.yunohost.org/ci/badges/libreddit.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/libreddit.maintain.svg)  
[![Installer Libreddit avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=libreddit)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Libreddit rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Libreddit is a portmanteau of "libre" (meaning freedom) and "Reddit". It is a private front-end like Invidious but for Reddit. Browse the coldest takes of r/unpopularopinion without being tracked.

### Features

    🚀 Fast: written in Rust for blazing fast speeds and memory safety
    ☁️ Light: no JavaScript, no ads, no tracking, no bloat
    🕵 Private: all requests are proxied through the server, including media
    🔒 Secure: strong Content Security Policy prevents browser requests to Reddit


**Version incluse :** 0.22.6~ynh1

**Démo :** https://libreddit.spike.codes/

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Documentations et ressources

* Site officiel de l'app : https://libreddit.spike.codes/
* Dépôt de code officiel de l'app : https://github.com/spikecodes/libreddit
* Documentation YunoHost pour cette app : https://yunohost.org/app_libreddit
* Signaler un bug : https://github.com/YunoHost-Apps/libreddit_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
ou
sudo yunohost app upgrade libreddit -u https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps