<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Libreddit pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/libreddit.svg)](https://dash.yunohost.org/appci/app/libreddit) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/libreddit.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/libreddit.maintain.svg)

[![Installer Libreddit avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=libreddit)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Libreddit rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Libreddit est un mot-valise de "libre" (qui signifie liberté) et "Reddit". C'est une interface privée comme Invidious mais pour Reddit. Parcourez les prises les plus froides de r/unpopularopinion sans être suivi.

### Caractéristiques

- Écrit en Rust pour des vitesses ultra rapides et la sécurité de la mémoire
- Pas de JavaScript, pas de publicité, pas de suivi, pas de ballonnement
- Toutes les requêtes sont transmises via le serveur, y compris les médias
- Une politique de sécurité du contenu solide empêche les requêtes du navigateur à Reddit

**Version incluse :** 0.30.1~ynh4

**Démo :** <https://libreddit.spike.codes/>

## Captures d’écran

![Capture d’écran de Libreddit](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://libreddit.spike.codes/>
- Dépôt de code officiel de l’app : <https://github.com/spikecodes/libreddit>
- YunoHost Store : <https://apps.yunohost.org/app/libreddit>
- Signaler un bug : <https://github.com/YunoHost-Apps/libreddit_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
ou
sudo yunohost app upgrade libreddit -u https://github.com/YunoHost-Apps/libreddit_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
