<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Shiori untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/shiori)](https://ci-apps.yunohost.org/ci/apps/shiori/)
![Status kerja](https://apps.yunohost.org/badge/state/shiori)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/shiori)

[![Pasang Shiori dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shiori)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Shiori secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Shiori is a simple bookmarks manager written in Go language. Intended as a simple clone of Pocket. You can use it as command line application or as web application. This application is distributed as a single binary, which means it can be installed and used easily.

### Features

- Simple and clean command line interface.
- Basic bookmarks management i.e. add, edit and delete.
- Search bookmarks by their title, tags, URL and page content.
- Import and export bookmarks from and to Netscape Bookmark file.
- Simple web interface for those who don't want to use a command line app.
- Where possible, by default shiori will download a static copy of the webpage in simple text and HTML format, which later can be used as an offline archive for that page.


**Versi terkirim:** 1.7.4~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Shiori](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Dokumentasi pengguna resmi: <https://github.com/go-shiori/shiori/wiki/Usage>
- Dokumentasi admin resmi: <https://github.com/go-shiori/shiori/wiki>
- Depot kode aplikasi hulu: <https://github.com/go-shiori/shiori>
- Gudang YunoHost: <https://apps.yunohost.org/app/shiori>
- Laporkan bug: <https://github.com/YunoHost-Apps/shiori_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/shiori_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
atau
sudo yunohost app upgrade shiori -u https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
