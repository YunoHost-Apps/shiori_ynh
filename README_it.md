<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Shiori per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/shiori.svg)](https://dash.yunohost.org/appci/app/shiori) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/shiori.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/shiori.maintain.svg)

[![Installa Shiori con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shiori)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Shiori su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Shiori is a simple bookmarks manager written in Go language. Intended as a simple clone of Pocket. You can use it as command line application or as web application. This application is distributed as a single binary, which means it can be installed and used easily.

### Features

- Simple and clean command line interface.
- Basic bookmarks management i.e. add, edit and delete.
- Search bookmarks by their title, tags, URL and page content.
- Import and export bookmarks from and to Netscape Bookmark file.
- Simple web interface for those who don't want to use a command line app.
- Where possible, by default shiori will download a static copy of the webpage in simple text and HTML format, which later can be used as an offline archive for that page.


**Versione pubblicata:** 1.6.1~ynh1

## Screenshot

![Screenshot di Shiori](./doc/screenshots/screenshot.png)

## Documentazione e risorse

- Documentazione ufficiale per gli utenti: <https://github.com/go-shiori/shiori/wiki/Usage>
- Documentazione ufficiale per gli amministratori: <https://github.com/go-shiori/shiori/wiki>
- Repository upstream del codice dell’app: <https://github.com/go-shiori/shiori>
- Store di YunoHost: <https://apps.yunohost.org/app/shiori>
- Segnala un problema: <https://github.com/YunoHost-Apps/shiori_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/shiori_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
o
sudo yunohost app upgrade shiori -u https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
