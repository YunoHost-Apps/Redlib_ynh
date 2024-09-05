<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Libreddit YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/libreddit.svg)](https://ci-apps.yunohost.org/ci/apps/libreddit/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/libreddit.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/libreddit.maintain.svg)

[![Instalatu Libreddit YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=libreddit)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Libreddit YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Libreddit is a portmanteau of "libre" (meaning freedom) and "Reddit". It is a private front-end like Invidious but for Reddit. Browse the coldest takes of r/unpopularopinion without being tracked.

### Features

- Written in Rust for blazing fast speeds and memory safety
- No JavaScript, no ads, no tracking, no bloat
- All requests are proxied through the server, including media
- Strong Content Security Policy prevents browser requests to Reddit


**Paketatutako bertsioa:** 0.35.1~ynh3

**Demoa:** <https://libreddit.spike.codes/>

## Pantaila-argazkiak

![Libreddit(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://libreddit.spike.codes/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/spikecodes/libreddit>
- YunoHost Denda: <https://apps.yunohost.org/app/libreddit>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/libreddit_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
edo
sudo yunohost app upgrade libreddit -u https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
