# Shiori pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/shiori.svg)](https://dash.yunohost.org/appci/app/shiori) ![](https://ci-apps.yunohost.org/ci/badges/shiori.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/shiori.maintain.svg)  
[![Installer Shiori avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shiori)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Shiori rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Shiori is a simple bookmarks manager written in Go language. Intended as a simple clone of Pocket. You can use it as command line application or as web application. This application is distributed as a single binary, which means it can be installed and used easily.

### Features

- Simple and clean command line interface.
- Basic bookmarks management i.e. add, edit and delete.
- Search bookmarks by their title, tags, url and page content.
- Import and export bookmarks from and to Netscape Bookmark file.
- Portable, thanks to its single binary format and sqlite3 database
- Simple web interface for those who don't want to use a command line app.
- Where possible, by default shiori will download a static copy of the webpage in simple text and HTML format, which later can be used as an offline archive for that page.



**Version incluse :** 1.5.0~ynh1

**Démo :** https://demo.example.com

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

username: shiori
password: gopher

## Documentations et ressources

* Site officiel de l'app : https://github.com/go-shiori/shiori
* Documentation officielle utilisateur : https://github.com/go-shiori/shiori/wiki/Usage
* Documentation officielle de l'admin : https://github.com/go-shiori/shiori/wiki
* Dépôt de code officiel de l'app : https://github.com/go-shiori/shiori
* Documentation YunoHost pour cette app : https://yunohost.org/app_shiori
* Signaler un bug : https://github.com/YunoHost-Apps/shiori_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/shiori_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
ou
sudo yunohost app upgrade shiori -u https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps