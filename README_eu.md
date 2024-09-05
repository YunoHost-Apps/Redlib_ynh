<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Redlib YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/redlib.svg)](https://ci-apps.yunohost.org/ci/apps/redlib/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/redlib.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/redlib.maintain.svg)

[![Instalatu Redlib YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=redlib)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Redlib YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Redlib is an alternative private front-end to Reddit, with its origins in Libreddit. It is a private front-end like Invidious but for Reddit. Browse the coldest takes of r/unpopularopinion without being tracked.

### Features

- Written in Rust for blazing fast speeds and memory safety
- No JavaScript, no ads, no tracking, no bloat
- All requests are proxied through the server, including media
- Strong Content Security Policy prevents browser requests to Reddit


**Paketatutako bertsioa:** 0.35.1~ynh4

## Pantaila-argazkiak

![Redlib(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/redlib-org/redlib>
- YunoHost Denda: <https://apps.yunohost.org/app/redlib>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/redlib_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/redlib_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/redlib_ynh/tree/testing --debug
edo
sudo yunohost app upgrade redlib -u https://github.com/YunoHost-Apps/redlib_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
