<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Cloud Torrent YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/cloud-torrent.svg)](https://dash.yunohost.org/appci/app/cloud-torrent) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/cloud-torrent.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/cloud-torrent.maintain.svg)

[![Instalatu Cloud Torrent YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cloud-torrent)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Cloud Torrent YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

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


**Paketatutako bertsioa:** 0.9.1~ynh1

## Pantaila-argazkiak

![Cloud Torrent(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Administratzaileen dokumentazio ofiziala: <https://github.com/jpillora/cloud-torrent/wiki/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/jpillora/cloud-torrent>
- YunoHost Denda: <https://apps.yunohost.org/app/cloud-torrent>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/cloud-torrent_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/cloud-torrent_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cloud-torrent_ynh/tree/testing --debug
edo
sudo yunohost app upgrade cloud-torrent -u https://github.com/YunoHost-Apps/cloud-torrent_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
