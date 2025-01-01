<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Shiori YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/shiori)](https://ci-apps.yunohost.org/ci/apps/shiori/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/shiori)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/shiori)

[![Instalatu Shiori YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shiori)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Shiori YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Shiori is a simple bookmarks manager written in Go language. Intended as a simple clone of Pocket. You can use it as command line application or as web application. This application is distributed as a single binary, which means it can be installed and used easily.

### Features

- Simple and clean command line interface.
- Basic bookmarks management i.e. add, edit and delete.
- Search bookmarks by their title, tags, URL and page content.
- Import and export bookmarks from and to Netscape Bookmark file.
- Simple web interface for those who don't want to use a command line app.
- Where possible, by default shiori will download a static copy of the webpage in simple text and HTML format, which later can be used as an offline archive for that page.


**Paketatutako bertsioa:** 1.7.2~ynh2

## Pantaila-argazkiak

![Shiori(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Erabiltzaileen dokumentazio ofiziala: <https://github.com/go-shiori/shiori/wiki/Usage>
- Administratzaileen dokumentazio ofiziala: <https://github.com/go-shiori/shiori/wiki>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/go-shiori/shiori>
- YunoHost Denda: <https://apps.yunohost.org/app/shiori>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/shiori_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/shiori_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
edo
sudo yunohost app upgrade shiori -u https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
