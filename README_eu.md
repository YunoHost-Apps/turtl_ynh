<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Turtl YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/turtl.svg)](https://dash.yunohost.org/appci/app/turtl) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/turtl.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/turtl.maintain.svg)

[![Instalatu Turtl YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=turtl)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Turtl YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

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


**Paketatutako bertsioa:** 2021.03.05~ynh1

## Pantaila-argazkiak

![Turtl(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Mantendu gabeko paketea**: YunoHost pakete honek ez du mantenduko duenik, bere gain hartuko duen norbaiten beharra dauka. Honek esan nahi duena da mantentze-lanak minimoak izango direla eta aplikazioa erabiltzen ez duten boluntarioek egingo dituztela lanok; denborak aurrera egin ahala fidagarri izateari utziko dio. [Aplikazioak nola paketatu](https://yunohost.org/packaging_apps_intro) ikas dezakezu, zure gain hartu nahi baduzu.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://turtlapp.com>
- Administratzaileen dokumentazio ofiziala: <https://turtlapp.com/docs/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/turtl/server>
- YunoHost Denda: <https://apps.yunohost.org/app/turtl>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/turtl_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/turtl_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/turtl_ynh/tree/testing --debug
edo
sudo yunohost app upgrade turtl -u https://github.com/YunoHost-Apps/turtl_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
