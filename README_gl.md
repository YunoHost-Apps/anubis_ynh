<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Anubis para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/anubis)](https://ci-apps.yunohost.org/ci/apps/anubis/)
![Estado de funcionamento](https://apps.yunohost.org/badge/state/anubis)
![Estado de mantemento](https://apps.yunohost.org/badge/maintained/anubis)

[![Instalar Anubis con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=anubis)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Anubis de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Anubis weighs the soul of your connection using a sha256 proof-of-work challenge in order to protect upstream resources from scraper bots.
This program is designed to help protect the small internet from the endless storm of requests that flood in from AI companies. Anubis is as lightweight as possible to ensure that everyone can afford to protect the communities closest to them.
Anubis is a bit of a nuclear response. This will result in your website being blocked from smaller scrapers and may inhibit "good bots" like the Internet Archive. You can configure bot policy definitions to explicitly allowlist them and we are working on a curated set of "known good" bots to allow for a compromise between discoverability and uptime.


**Versión proporcionada:** 1.14.2.~ynh1

## Capturas de pantalla

![Captura de pantalla de Anubis](./doc/screenshots/example.jpg)

## Documentación e recursos

- Web oficial da app: <https://anubis.techaro.lol/>
- Documentación oficial para admin: <https://anubis.techaro.lol/docs/admin/installation>
- Repositorio de orixe do código: <https://github.com/TecharoHQ/anubis>
- Tenda YunoHost: <https://apps.yunohost.org/app/anubis>
- Informar dun problema: <https://github.com/YunoHost-Apps/anubis_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/anubis_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/anubis_ynh/tree/testing --debug
ou
sudo yunohost app upgrade anubis -u https://github.com/YunoHost-Apps/anubis_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
