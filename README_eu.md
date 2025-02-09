<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Jangouts YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/jangouts)](https://ci-apps.yunohost.org/ci/apps/jangouts/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/jangouts)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/jangouts)

[![Instalatu Jangouts YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=jangouts)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Jangouts YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Jangouts (for "Janus Hangouts") is a solution for videoconferencing based on WebRTC and the excellent Janus Gateway with a user interface loosely inspired by Google Hangouts. It aims to provide a completely self-hosted open source alternative to Google Hangouts and similar solutions. Currently Jangouts supports conferences with video, audio, screen sharing and textual chat organized into an unlimited amount of conference rooms with a configurable limit of participants per room.


**Paketatutako bertsioa:** 0.6.0~ynh1

## Pantaila-argazkiak

![Jangouts(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/jangouts/jangouts>
- YunoHost Denda: <https://apps.yunohost.org/app/jangouts>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/jangouts_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/jangouts_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/jangouts_ynh/tree/testing --debug
edo
sudo yunohost app upgrade jangouts -u https://github.com/YunoHost-Apps/jangouts_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
