<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Jangouts pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/jangouts)](https://ci-apps.yunohost.org/ci/apps/jangouts/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/jangouts)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/jangouts)

[![Installer Jangouts avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=jangouts)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Jangouts rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Jangouts (pour « Janus Hangouts ») est une solution de vidéoconférence basée sur WebRTC et l'excellente passerelle Janus avec une interface utilisateur vaguement inspirée de Google Hangouts. Elle vise à fournir une alternative open source entièrement auto-hébergée à Google Hangouts et à d'autres solutions similaires. Actuellement, Jangouts prend en charge les conférences avec vidéo, audio, partage d'écran et chat textuel organisées dans un nombre illimité de salles de conférence avec une limite configurable de participants par salle.


**Version incluse :** 0.6.0~ynh1

## Captures d’écran

![Capture d’écran de Jangouts](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Dépôt de code officiel de l’app : <https://github.com/jangouts/jangouts>
- YunoHost Store : <https://apps.yunohost.org/app/jangouts>
- Signaler un bug : <https://github.com/YunoHost-Apps/jangouts_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/jangouts_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/jangouts_ynh/tree/testing --debug
ou
sudo yunohost app upgrade jangouts -u https://github.com/YunoHost-Apps/jangouts_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
