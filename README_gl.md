<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Libreddit para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/libreddit.svg)](https://ci-apps.yunohost.org/ci/apps/libreddit/) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/libreddit.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/libreddit.maintain.svg)

[![Instalar Libreddit con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=libreddit)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Libreddit de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Libreddit is a portmanteau of "libre" (meaning freedom) and "Reddit". It is a private front-end like Invidious but for Reddit. Browse the coldest takes of r/unpopularopinion without being tracked.

### Features

- Written in Rust for blazing fast speeds and memory safety
- No JavaScript, no ads, no tracking, no bloat
- All requests are proxied through the server, including media
- Strong Content Security Policy prevents browser requests to Reddit


**Versión proporcionada:** 3.0.0~ynh1

**Demo:** <https://libreddit.spike.codes/>

## Capturas de pantalla

![Captura de pantalla de Libreddit](./doc/screenshots/screenshot.png)

## Documentación e recursos

- Web oficial da app: <https://libreddit.spike.codes/>
- Repositorio de orixe do código: <https://github.com/spikecodes/libreddit>
- Tenda YunoHost: <https://apps.yunohost.org/app/libreddit>
- Informar dun problema: <https://github.com/YunoHost-Apps/libreddit_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
ou
sudo yunohost app upgrade libreddit -u https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
