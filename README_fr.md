<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Shiori pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/shiori.svg)](https://dash.yunohost.org/appci/app/shiori) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/shiori.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/shiori.maintain.svg)

[![Installer Shiori avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shiori)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Shiori rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Shiori est un simple gestionnaire de signets écrit en langage Go. Conçu comme un simple clone de Pocket. Vous pouvez l'utiliser comme application de ligne de commande ou comme application Web. Cette application est distribuée sous la forme d'un binaire unique, ce qui signifie qu'elle peut être installée et utilisée facilement.

### Caractéristiques

- Interface de ligne de commande simple et propre.
- Gestion des signets de base, c'est-à-dire ajouter, modifier et supprimer.
- Recherchez des signets par leur titre, leurs balises, leur URL et le contenu de la page.
- Importer et exporter des signets depuis et vers le fichier Netscape Bookmark.
- Interface Web simple pour ceux qui ne veulent pas utiliser une application en ligne de commande.
- Dans la mesure du possible, shiori téléchargera par défaut une copie statique de la page Web au format texte simple et HTML, qui pourra ensuite être utilisée comme archive hors ligne pour cette page.


**Version incluse :** 1.6.1~ynh1

## Captures d’écran

![Capture d’écran de Shiori](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Documentation officielle utilisateur : <https://github.com/go-shiori/shiori/wiki/Usage>
- Documentation officielle de l’admin : <https://github.com/go-shiori/shiori/wiki>
- Dépôt de code officiel de l’app : <https://github.com/go-shiori/shiori>
- YunoHost Store : <https://apps.yunohost.org/app/shiori>
- Signaler un bug : <https://github.com/YunoHost-Apps/shiori_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/shiori_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
ou
sudo yunohost app upgrade shiori -u https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
