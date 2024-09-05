<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Redlib para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/redlib.svg)](https://ci-apps.yunohost.org/ci/apps/redlib/) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/redlib.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/redlib.maintain.svg)

[![Instalar Redlib con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=redlib)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Redlib de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Redlib is an alternative private front-end to Reddit, with its origins in Libreddit. It is a private front-end like Invidious but for Reddit. Browse the coldest takes of r/unpopularopinion without being tracked.

### Features

- Written in Rust for blazing fast speeds and memory safety
- No JavaScript, no ads, no tracking, no bloat
- All requests are proxied through the server, including media
- Strong Content Security Policy prevents browser requests to Reddit


**Versión proporcionada:** 0.35.1~ynh4

## Capturas de pantalla

![Captura de pantalla de Redlib](./doc/screenshots/screenshot.png)

## Documentación e recursos

- Repositorio de orixe do código: <https://github.com/redlib-org/redlib>
- Tenda YunoHost: <https://apps.yunohost.org/app/redlib>
- Informar dun problema: <https://github.com/YunoHost-Apps/redlib_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/redlib_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/redlib_ynh/tree/testing --debug
ou
sudo yunohost app upgrade redlib -u https://github.com/YunoHost-Apps/redlib_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
