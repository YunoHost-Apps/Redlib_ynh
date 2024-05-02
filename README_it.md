<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Libreddit per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/libreddit.svg)](https://dash.yunohost.org/appci/app/libreddit) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/libreddit.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/libreddit.maintain.svg)

[![Installa Libreddit con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=libreddit)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Libreddit su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Libreddit is a portmanteau of "libre" (meaning freedom) and "Reddit". It is a private front-end like Invidious but for Reddit. Browse the coldest takes of r/unpopularopinion without being tracked.

### Features

- Written in Rust for blazing fast speeds and memory safety
- No JavaScript, no ads, no tracking, no bloat
- All requests are proxied through the server, including media
- Strong Content Security Policy prevents browser requests to Reddit


**Versione pubblicata:** 0.30.1~ynh4

**Prova:** <https://libreddit.spike.codes/>

## Screenshot

![Screenshot di Libreddit](./doc/screenshots/screenshot.png)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://libreddit.spike.codes/>
- Repository upstream del codice dell’app: <https://github.com/spikecodes/libreddit>
- Store di YunoHost: <https://apps.yunohost.org/app/libreddit>
- Segnala un problema: <https://github.com/YunoHost-Apps/libreddit_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
o
sudo yunohost app upgrade libreddit -u https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
