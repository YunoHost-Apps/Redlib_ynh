<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Libreddit untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/libreddit.svg)](https://ci-apps.yunohost.org/ci/apps/libreddit/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/libreddit.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/libreddit.maintain.svg)

[![Pasang Libreddit dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=libreddit)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Libreddit secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Libreddit is a portmanteau of "libre" (meaning freedom) and "Reddit". It is a private front-end like Invidious but for Reddit. Browse the coldest takes of r/unpopularopinion without being tracked.

### Features

- Written in Rust for blazing fast speeds and memory safety
- No JavaScript, no ads, no tracking, no bloat
- All requests are proxied through the server, including media
- Strong Content Security Policy prevents browser requests to Reddit


**Versi terkirim:** 0.35.1~ynh2

**Demo:** <https://libreddit.spike.codes/>

## Tangkapan Layar

![Tangkapan Layar pada Libreddit](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://libreddit.spike.codes/>
- Depot kode aplikasi hulu: <https://github.com/spikecodes/libreddit>
- Gudang YunoHost: <https://apps.yunohost.org/app/libreddit>
- Laporkan bug: <https://github.com/YunoHost-Apps/libreddit_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
atau
sudo yunohost app upgrade libreddit -u https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
