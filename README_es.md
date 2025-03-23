<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Anubis para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/anubis)](https://ci-apps.yunohost.org/ci/apps/anubis/)
![Estado funcional](https://apps.yunohost.org/badge/state/anubis)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/anubis)

[![Instalar Anubis con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=anubis)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarAnubis rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Anubis weighs the soul of your connection using a sha256 proof-of-work challenge in order to protect upstream resources from scraper bots.
This program is designed to help protect the small internet from the endless storm of requests that flood in from AI companies. Anubis is as lightweight as possible to ensure that everyone can afford to protect the communities closest to them.
Anubis is a bit of a nuclear response. This will result in your website being blocked from smaller scrapers and may inhibit "good bots" like the Internet Archive. You can configure bot policy definitions to explicitly allowlist them and we are working on a curated set of "known good" bots to allow for a compromise between discoverability and uptime.


**Versión actual:** 1.14.2.~ynh1
## Documentaciones y recursos

- Sitio web oficial: <https://anubis.techaro.lol/>
- Documentación administrador oficial: <https://anubis.techaro.lol/docs/admin/installation>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/TecharoHQ/anubis>
- Catálogo YunoHost: <https://apps.yunohost.org/app/anubis>
- Reportar un error: <https://github.com/YunoHost-Apps/anubis_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/anubis_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/anubis_ynh/tree/testing --debug
o
sudo yunohost app upgrade anubis -u https://github.com/YunoHost-Apps/anubis_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
