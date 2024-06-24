<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Shiori para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/shiori.svg)](https://dash.yunohost.org/appci/app/shiori) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/shiori.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/shiori.maintain.svg)

[![Instalar Shiori con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shiori)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Shiori de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Shiori is a simple bookmarks manager written in Go language. Intended as a simple clone of Pocket. You can use it as command line application or as web application. This application is distributed as a single binary, which means it can be installed and used easily.

### Features

- Simple and clean command line interface.
- Basic bookmarks management i.e. add, edit and delete.
- Search bookmarks by their title, tags, URL and page content.
- Import and export bookmarks from and to Netscape Bookmark file.
- Simple web interface for those who don't want to use a command line app.
- Where possible, by default shiori will download a static copy of the webpage in simple text and HTML format, which later can be used as an offline archive for that page.


**Versión proporcionada:** 1.7.0~ynh2

## Capturas de pantalla

![Captura de pantalla de Shiori](./doc/screenshots/screenshot.png)

## Documentación e recursos

- Documentación oficial para usuarias: <https://github.com/go-shiori/shiori/wiki/Usage>
- Documentación oficial para admin: <https://github.com/go-shiori/shiori/wiki>
- Repositorio de orixe do código: <https://github.com/go-shiori/shiori>
- Tenda YunoHost: <https://apps.yunohost.org/app/shiori>
- Informar dun problema: <https://github.com/YunoHost-Apps/shiori_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/shiori_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
ou
sudo yunohost app upgrade shiori -u https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
