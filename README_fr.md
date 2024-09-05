<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Redlib pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/redlib.svg)](https://ci-apps.yunohost.org/ci/apps/redlib/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/redlib.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/redlib.maintain.svg)

[![Installer Redlib avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=redlib)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Redlib rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Redlib est une interface privée alternative à Reddit, dont les origines se trouvent dans Libreddit. C'est une interface privée comme Invidious mais pour Reddit. Parcourez les prises les plus froides de r/unpopularopinion sans être suivi.

### Caractéristiques

- Écrit en Rust pour des vitesses ultra rapides et la sécurité de la mémoire
- Pas de JavaScript, pas de publicité, pas de suivi, pas de ballonnement
- Toutes les requêtes sont transmises via le serveur, y compris les médias
- Une politique de sécurité du contenu solide empêche les requêtes du navigateur à Reddit

**Version incluse :** 0.35.1~ynh4

## Captures d’écran

![Capture d’écran de Redlib](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Dépôt de code officiel de l’app : <https://github.com/redlib-org/redlib>
- YunoHost Store : <https://apps.yunohost.org/app/redlib>
- Signaler un bug : <https://github.com/YunoHost-Apps/redlib_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/redlib_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/redlib_ynh/tree/testing --debug
ou
sudo yunohost app upgrade redlib -u https://github.com/YunoHost-Apps/redlib_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
