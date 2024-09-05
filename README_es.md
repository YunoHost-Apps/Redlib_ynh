<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Redlib para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/redlib.svg)](https://ci-apps.yunohost.org/ci/apps/redlib/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/redlib.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/redlib.maintain.svg)

[![Instalar Redlib con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=redlib)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarRedlib rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Redlib is an alternative private front-end to Reddit, with its origins in Libreddit. It is a private front-end like Invidious but for Reddit. Browse the coldest takes of r/unpopularopinion without being tracked.

### Features

- Written in Rust for blazing fast speeds and memory safety
- No JavaScript, no ads, no tracking, no bloat
- All requests are proxied through the server, including media
- Strong Content Security Policy prevents browser requests to Reddit


**Versión actual:** 0.35.1~ynh4

## Capturas

![Captura de Redlib](./doc/screenshots/screenshot.png)

## Documentaciones y recursos

- Repositorio del código fuente oficial de la aplicación : <https://github.com/redlib-org/redlib>
- Catálogo YunoHost: <https://apps.yunohost.org/app/redlib>
- Reportar un error: <https://github.com/YunoHost-Apps/redlib_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/redlib_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/redlib_ynh/tree/testing --debug
o
sudo yunohost app upgrade redlib -u https://github.com/YunoHost-Apps/redlib_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
