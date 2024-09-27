<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Shiori voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/shiori.svg)](https://ci-apps.yunohost.org/ci/apps/shiori/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/shiori.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/shiori.maintain.svg)

[![Shiori met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shiori)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Shiori snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Shiori is a simple bookmarks manager written in Go language. Intended as a simple clone of Pocket. You can use it as command line application or as web application. This application is distributed as a single binary, which means it can be installed and used easily.

### Features

- Simple and clean command line interface.
- Basic bookmarks management i.e. add, edit and delete.
- Search bookmarks by their title, tags, URL and page content.
- Import and export bookmarks from and to Netscape Bookmark file.
- Simple web interface for those who don't want to use a command line app.
- Where possible, by default shiori will download a static copy of the webpage in simple text and HTML format, which later can be used as an offline archive for that page.


**Geleverde versie:** 1.7.0~ynh3

## Schermafdrukken

![Schermafdrukken van Shiori](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele gebruikersdocumentatie: <https://github.com/go-shiori/shiori/wiki/Usage>
- Officiele beheerdersdocumentatie: <https://github.com/go-shiori/shiori/wiki>
- Upstream app codedepot: <https://github.com/go-shiori/shiori>
- YunoHost-store: <https://apps.yunohost.org/app/shiori>
- Meld een bug: <https://github.com/YunoHost-Apps/shiori_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/shiori_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
of
sudo yunohost app upgrade shiori -u https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
