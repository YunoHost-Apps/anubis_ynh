<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Anubis YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/anubis)](https://ci-apps.yunohost.org/ci/apps/anubis/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/anubis)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/anubis)

[![Instalatu Anubis YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=anubis)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Anubis YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Anubis weighs the soul of your connection using a sha256 proof-of-work challenge in order to protect upstream resources from scraper bots.
This program is designed to help protect the small internet from the endless storm of requests that flood in from AI companies. Anubis is as lightweight as possible to ensure that everyone can afford to protect the communities closest to them.
Anubis is a bit of a nuclear response. This will result in your website being blocked from smaller scrapers and may inhibit "good bots" like the Internet Archive. You can configure bot policy definitions to explicitly allowlist them and we are working on a curated set of "known good" bots to allow for a compromise between discoverability and uptime.


**Paketatutako bertsioa:** 1.14.2.~ynh1

## Pantaila-argazkiak

![Anubis(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://anubis.techaro.lol/>
- Administratzaileen dokumentazio ofiziala: <https://anubis.techaro.lol/docs/admin/installation>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/TecharoHQ/anubis>
- YunoHost Denda: <https://apps.yunohost.org/app/anubis>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/anubis_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/anubis_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/anubis_ynh/tree/testing --debug
edo
sudo yunohost app upgrade anubis -u https://github.com/YunoHost-Apps/anubis_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
