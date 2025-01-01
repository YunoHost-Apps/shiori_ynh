<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Shiori para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/shiori)](https://ci-apps.yunohost.org/ci/apps/shiori/)
![Estado funcional](https://apps.yunohost.org/badge/state/shiori)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/shiori)

[![Instalar Shiori con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shiori)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarShiori rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Shiori is a simple bookmarks manager written in Go language. Intended as a simple clone of Pocket. You can use it as command line application or as web application. This application is distributed as a single binary, which means it can be installed and used easily.

### Features

- Simple and clean command line interface.
- Basic bookmarks management i.e. add, edit and delete.
- Search bookmarks by their title, tags, URL and page content.
- Import and export bookmarks from and to Netscape Bookmark file.
- Simple web interface for those who don't want to use a command line app.
- Where possible, by default shiori will download a static copy of the webpage in simple text and HTML format, which later can be used as an offline archive for that page.


**Versión actual:** 1.7.2~ynh2

## Capturas

![Captura de Shiori](./doc/screenshots/screenshot.png)

## Documentaciones y recursos

- Documentación usuario oficial: <https://github.com/go-shiori/shiori/wiki/Usage>
- Documentación administrador oficial: <https://github.com/go-shiori/shiori/wiki>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/go-shiori/shiori>
- Catálogo YunoHost: <https://apps.yunohost.org/app/shiori>
- Reportar un error: <https://github.com/YunoHost-Apps/shiori_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/shiori_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
o
sudo yunohost app upgrade shiori -u https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
