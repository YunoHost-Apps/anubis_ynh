<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Anubis voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/anubis)](https://ci-apps.yunohost.org/ci/apps/anubis/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/anubis)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/anubis)

[![Anubis met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=anubis)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Anubis snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Anubis weighs the soul of your connection using a sha256 proof-of-work challenge in order to protect upstream resources from scraper bots.
This program is designed to help protect the small internet from the endless storm of requests that flood in from AI companies. Anubis is as lightweight as possible to ensure that everyone can afford to protect the communities closest to them.
Anubis is a bit of a nuclear response. This will result in your website being blocked from smaller scrapers and may inhibit "good bots" like the Internet Archive. You can configure bot policy definitions to explicitly allowlist them and we are working on a curated set of "known good" bots to allow for a compromise between discoverability and uptime.


**Geleverde versie:** 1.14.2.~ynh1

## Schermafdrukken

![Schermafdrukken van Anubis](./doc/screenshots/example.jpg)

## Documentatie en bronnen

- Officiele website van de app: <https://anubis.techaro.lol/>
- Officiele beheerdersdocumentatie: <https://anubis.techaro.lol/docs/admin/installation>
- Upstream app codedepot: <https://github.com/TecharoHQ/anubis>
- YunoHost-store: <https://apps.yunohost.org/app/anubis>
- Meld een bug: <https://github.com/YunoHost-Apps/anubis_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/anubis_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/anubis_ynh/tree/testing --debug
of
sudo yunohost app upgrade anubis -u https://github.com/YunoHost-Apps/anubis_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
