<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Cloud Torrent para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/cloud-torrent.svg)](https://dash.yunohost.org/appci/app/cloud-torrent) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/cloud-torrent.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/cloud-torrent.maintain.svg)

[![Instalar Cloud Torrent con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cloud-torrent)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Cloud Torrent de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

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


**Versión proporcionada:** 0.9.1~ynh1

## Capturas de pantalla

![Captura de pantalla de Cloud Torrent](./doc/screenshots/screenshot.png)

## Documentación e recursos

- Documentación oficial para admin: <https://github.com/jpillora/cloud-torrent/wiki/>
- Repositorio de orixe do código: <https://github.com/jpillora/cloud-torrent>
- Tenda YunoHost: <https://apps.yunohost.org/app/cloud-torrent>
- Informar dun problema: <https://github.com/YunoHost-Apps/cloud-torrent_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/cloud-torrent_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cloud-torrent_ynh/tree/testing --debug
ou
sudo yunohost app upgrade cloud-torrent -u https://github.com/YunoHost-Apps/cloud-torrent_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
