<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Libreddit para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/libreddit.svg)](https://ci-apps.yunohost.org/ci/apps/libreddit/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/libreddit.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/libreddit.maintain.svg)

[![Instalar Libreddit con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=libreddit)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarLibreddit rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Libreddit is a portmanteau of "libre" (meaning freedom) and "Reddit". It is a private front-end like Invidious but for Reddit. Browse the coldest takes of r/unpopularopinion without being tracked.

### Features

- Written in Rust for blazing fast speeds and memory safety
- No JavaScript, no ads, no tracking, no bloat
- All requests are proxied through the server, including media
- Strong Content Security Policy prevents browser requests to Reddit


**Versión actual:** 3.0.0~ynh1

**Demo:** <https://libreddit.spike.codes/>

## Capturas

![Captura de Libreddit](./doc/screenshots/screenshot.png)

## Documentaciones y recursos

- Sitio web oficial: <https://libreddit.spike.codes/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/spikecodes/libreddit>
- Catálogo YunoHost: <https://apps.yunohost.org/app/libreddit>
- Reportar un error: <https://github.com/YunoHost-Apps/libreddit_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
o
sudo yunohost app upgrade libreddit -u https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
