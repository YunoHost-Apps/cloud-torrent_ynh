<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Cloud Torrent pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/cloud-torrent.svg)](https://dash.yunohost.org/appci/app/cloud-torrent) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/cloud-torrent.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/cloud-torrent.maintain.svg)

[![Installer Cloud Torrent avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cloud-torrent)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Cloud Torrent rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Cloud-Torrent is a a self-hosted remote torrent client, written in Go (golang). Started torrents remotely, download sets of files on the local disk of the server, which are then retrievable or streamable via HTTP.

### Features

- Individual file download control (1.1.3+)
- Run external program on tasks completion
- Stops task when seeding ratio reached
- Download/Upload speed limiter
- Detailed transfer stats in web UI.
- Torrent Watcher
- Extra trackers from external source
- Protocol Handler to magnet
- Magnet RSS subscribing supported


**Version incluse :** 0.9.1~ynh1

## Captures d’écran

![Capture d’écran de Cloud Torrent](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Documentation officielle de l’admin : <https://github.com/jpillora/cloud-torrent/wiki/>
- Dépôt de code officiel de l’app : <https://github.com/jpillora/cloud-torrent>
- YunoHost Store : <https://apps.yunohost.org/app/cloud-torrent>
- Signaler un bug : <https://github.com/YunoHost-Apps/cloud-torrent_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/cloud-torrent_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cloud-torrent_ynh/tree/testing --debug
ou
sudo yunohost app upgrade cloud-torrent -u https://github.com/YunoHost-Apps/cloud-torrent_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
