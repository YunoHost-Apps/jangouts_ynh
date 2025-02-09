<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Jangouts для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/jangouts)](https://ci-apps.yunohost.org/ci/apps/jangouts/)
![Состояние работы](https://apps.yunohost.org/badge/state/jangouts)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/jangouts)

[![Установите Jangouts с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=jangouts)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Jangouts быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Jangouts (for "Janus Hangouts") is a solution for videoconferencing based on WebRTC and the excellent Janus Gateway with a user interface loosely inspired by Google Hangouts. It aims to provide a completely self-hosted open source alternative to Google Hangouts and similar solutions. Currently Jangouts supports conferences with video, audio, screen sharing and textual chat organized into an unlimited amount of conference rooms with a configurable limit of participants per room.


**Поставляемая версия:** 0.6.0~ynh1

## Снимки экрана

![Снимок экрана Jangouts](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Репозиторий кода главной ветки приложения: <https://github.com/jangouts/jangouts>
- Магазин YunoHost: <https://apps.yunohost.org/app/jangouts>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/jangouts_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/jangouts_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/jangouts_ynh/tree/testing --debug
или
sudo yunohost app upgrade jangouts -u https://github.com/YunoHost-Apps/jangouts_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
