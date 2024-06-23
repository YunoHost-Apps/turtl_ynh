<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Turtl para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/turtl.svg)](https://dash.yunohost.org/appci/app/turtl) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/turtl.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/turtl.maintain.svg)

[![Instalar Turtl con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=turtl)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarTurtl rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Turtl is a free online service that allows you to create, synchronize and find your notes, in an encrypted manner. 

### Features

- Different note types: text, bookmark, password, image, and file/document
- Client-side cryptography to keep all of your data safe
- Securely share with anyone without compromising the security of your data
- Sharing allows different permissions ranging from read-only to full ownership of shared content
- Find your notes easily. Turtl supports full-text search, filtering by tag (or lack of tag), and sort by create/edit date
- Attach photos, files, and documents to your notes. Files are stored securely just like the rest of your data.
- Browser extension makes bookmarking easy on desktop
- Share to Turtl on Android for easy bookmarking and file uploads
- Write notes in Markdown, an easy and natural way to format text
- TeX math expressions in notes for math people (surround them by $$ to use)
- Multiple translations (German, Spanish, French, and more)
- RTL text support for our Farsi/Hebrew/etc-speaking friends
- Export/import your entire profile for backup purposes or to move between servers
- Semi-offline mode (you only need to be connected to log in)
- A number of keyboard shortcuts for navigation the app without mouse (type ? in-app to see shortcuts)
- An open-source server allows you to host your own Turtl data


**Versión actual:** 2021.03.05~ynh1

## Capturas

![Captura de Turtl](./doc/screenshots/screenshot.png)

## :red_circle: Características no deseables

- **Package not maintained**: This YunoHost package is not actively maintained and needs adoption. This means that minimal maintenance is made by volunteers who don't use the app, so you should expect the app to lose reliability over time. You can [learn how to package](https://yunohost.org/packaging_apps_intro) if you'd like to adopt it.

## Documentaciones y recursos

- Sitio web oficial: <https://turtlapp.com>
- Documentación administrador oficial: <https://turtlapp.com/docs/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/turtl/server>
- Catálogo YunoHost: <https://apps.yunohost.org/app/turtl>
- Reportar un error: <https://github.com/YunoHost-Apps/turtl_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/turtl_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/turtl_ynh/tree/testing --debug
o
sudo yunohost app upgrade turtl -u https://github.com/YunoHost-Apps/turtl_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
