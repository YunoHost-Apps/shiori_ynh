<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Shiori для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/shiori)](https://ci-apps.yunohost.org/ci/apps/shiori/)
![Состояние работы](https://apps.yunohost.org/badge/state/shiori)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/shiori)

[![Установите Shiori с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shiori)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Shiori быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Shiori is a simple bookmarks manager written in Go language. Intended as a simple clone of Pocket. You can use it as command line application or as web application. This application is distributed as a single binary, which means it can be installed and used easily.

### Features

- Simple and clean command line interface.
- Basic bookmarks management i.e. add, edit and delete.
- Search bookmarks by their title, tags, URL and page content.
- Import and export bookmarks from and to Netscape Bookmark file.
- Simple web interface for those who don't want to use a command line app.
- Where possible, by default shiori will download a static copy of the webpage in simple text and HTML format, which later can be used as an offline archive for that page.


**Поставляемая версия:** 1.7.2~ynh1

## Снимки экрана

![Снимок экрана Shiori](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальная документация пользователя: <https://github.com/go-shiori/shiori/wiki/Usage>
- Официальная документация администратора: <https://github.com/go-shiori/shiori/wiki>
- Репозиторий кода главной ветки приложения: <https://github.com/go-shiori/shiori>
- Магазин YunoHost: <https://apps.yunohost.org/app/shiori>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/shiori_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/shiori_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
или
sudo yunohost app upgrade shiori -u https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
