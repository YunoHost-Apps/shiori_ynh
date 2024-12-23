<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Shiori dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/shiori)](https://ci-apps.yunohost.org/ci/apps/shiori/)
![Status działania](https://apps.yunohost.org/badge/state/shiori)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/shiori)

[![Zainstaluj Shiori z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shiori)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Shiori na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Shiori is a simple bookmarks manager written in Go language. Intended as a simple clone of Pocket. You can use it as command line application or as web application. This application is distributed as a single binary, which means it can be installed and used easily.

### Features

- Simple and clean command line interface.
- Basic bookmarks management i.e. add, edit and delete.
- Search bookmarks by their title, tags, URL and page content.
- Import and export bookmarks from and to Netscape Bookmark file.
- Simple web interface for those who don't want to use a command line app.
- Where possible, by default shiori will download a static copy of the webpage in simple text and HTML format, which later can be used as an offline archive for that page.


**Dostarczona wersja:** 1.7.2~ynh1

## Zrzuty ekranu

![Zrzut ekranu z Shiori](./doc/screenshots/screenshot.png)

## Dokumentacja i zasoby

- Oficjalna dokumentacja: <https://github.com/go-shiori/shiori/wiki/Usage>
- Oficjalna dokumentacja dla administratora: <https://github.com/go-shiori/shiori/wiki>
- Repozytorium z kodem źródłowym: <https://github.com/go-shiori/shiori>
- Sklep YunoHost: <https://apps.yunohost.org/app/shiori>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/shiori_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/shiori_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
lub
sudo yunohost app upgrade shiori -u https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
