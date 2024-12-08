<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Fluffychat pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/fluffychat)](https://ci-apps.yunohost.org/ci/apps/fluffychat/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/fluffychat)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/fluffychat)

[![Installer Fluffychat avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=fluffychat)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Fluffychat rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

FluffyChat est un client [[matrix](https://matrix.org)] open-source, à but non lucratif et mignon écrit en [Flutter](https://flutter.dev).  
Le but de cette app est de créer un client de messagerie instantanée facile d'utilisation, open-source et accessible pour tout le monde.


**Version incluse :** 1.23.0~ynh1

**Démo :** <https://fluffychat.im/web>

## Captures d’écran

![Capture d’écran de Fluffychat](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://fluffychat.im/>
- Documentation officielle utilisateur : <https://github.com/krille-chan/fluffychat/wiki#-user-guides>
- Dépôt de code officiel de l’app : <https://github.com/krille-chan/fluffychat>
- YunoHost Store : <https://apps.yunohost.org/app/fluffychat>
- Signaler un bug : <https://github.com/YunoHost-Apps/fluffychat_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/fluffychat_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/fluffychat_ynh/tree/testing --debug
ou
sudo yunohost app upgrade fluffychat -u https://github.com/YunoHost-Apps/fluffychat_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
