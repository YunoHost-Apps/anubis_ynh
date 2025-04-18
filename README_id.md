<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Anubis untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/anubis)](https://ci-apps.yunohost.org/ci/apps/anubis/)
![Status kerja](https://apps.yunohost.org/badge/state/anubis)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/anubis)

[![Pasang Anubis dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=anubis)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Anubis secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Anubis weighs the soul of your connection using a sha256 proof-of-work challenge in order to protect upstream resources from scraper bots.
This program is designed to help protect the small internet from the endless storm of requests that flood in from AI companies. Anubis is as lightweight as possible to ensure that everyone can afford to protect the communities closest to them.
Anubis is a bit of a nuclear response. This will result in your website being blocked from smaller scrapers and may inhibit "good bots" like the Internet Archive. You can configure bot policy definitions to explicitly allowlist them and we are working on a curated set of "known good" bots to allow for a compromise between discoverability and uptime.


**Versi terkirim:** 1.14.2~ynh1
## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://anubis.techaro.lol/>
- Dokumentasi admin resmi: <https://anubis.techaro.lol/docs/admin/installation>
- Depot kode aplikasi hulu: <https://github.com/TecharoHQ/anubis>
- Gudang YunoHost: <https://apps.yunohost.org/app/anubis>
- Laporkan bug: <https://github.com/YunoHost-Apps/anubis_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/anubis_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/anubis_ynh/tree/testing --debug
atau
sudo yunohost app upgrade anubis -u https://github.com/YunoHost-Apps/anubis_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
