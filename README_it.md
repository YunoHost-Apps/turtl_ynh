<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Turtl per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/turtl.svg)](https://dash.yunohost.org/appci/app/turtl) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/turtl.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/turtl.maintain.svg)

[![Installa Turtl con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=turtl)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Turtl su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

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


**Versione pubblicata:** 2021.03.05~ynh1

## Screenshot

![Screenshot di Turtl](./doc/screenshots/screenshot.png)

## :red_circle: Anti-funzionalità

- **Pacchetto non mantenuto**: Questo pacchetto di YunoHost non è più mantenuto e necessita di essere adottato.

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://turtlapp.com>
- Documentazione ufficiale per gli amministratori: <https://turtlapp.com/docs/>
- Repository upstream del codice dell’app: <https://github.com/turtl/server>
- Store di YunoHost: <https://apps.yunohost.org/app/turtl>
- Segnala un problema: <https://github.com/YunoHost-Apps/turtl_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/turtl_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/turtl_ynh/tree/testing --debug
o
sudo yunohost app upgrade turtl -u https://github.com/YunoHost-Apps/turtl_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
