# Changelog  
  
| modName    | Near Future Rovers (NFR) by MichaelV2.0                           |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-NC-ND-4.0+ARR                                               |
| author     | MichaelV2.0 and zer0Kerbal                                        |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/207911-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/NearFutureRovers)       |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/NearFutureRovers)     |
| spacedock  | (https://spacedock.info/mod/590)                                  |
| ckan       | NearFutureRovers                                                  |

## Version 2.0.99.1-prerelease - `<Спасибо evanisrael>` edition

* Released
  * 12 Jun 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

### Change Summary 2.0.99.1

* Add localization: Russian (Русский) -  Спасибо [evanisrael](https://github/evanisrael)

### Changes 2.0.99.1

#### Localization 2.0.99.1

* Add
  * Russian (Русский)
    * [ru.cfg] v1.0.0.0
    * Спасибо [evanisrael](https://github/evanisrael)
  Translation guides
    * [readme-ru.md] v1.0.1.0
    * [quickstart-ru.md] v1.0.0.0
    * Спасибо [evanisrael](https://github/evanisrael)
* Update
  * [ru.cfg] v1.0.1.0
  * add header, give credit
* closes #21 - Russian <ru.cfg>
* updates #13 - Localization - Master

#### Documentation 2.0.99.1

* Update
  * [readme.md] v1.0.1.0
  * [Attributions.md] v1.0.1.0
  * [Localizations.md] v1.0.1.0

### Status 2.0.99.1

* Issues
  * closes #38 - Near Future Rovers (NFR) 2.0.99.1-prerelease `<Спасибо evanisrael>` edition
  * closes #39 - 2.0.99.1 Additional Tasks

---

## Version 2.0.99.0-adoption - `<Thank you MichaelV2.0>` edition

* Released
  * 26 Apr 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

## Adoption by [zer0Kerbal](https://github.com/zer0Kerbal)

### Change Summary 2.0.99.0

* Update
* Lint
* and so much more
* DRAG_CUBES
* Cargo/Inventory
* Modernize
* Convert all textures to dds
* Add modcons to parts such as a fuel cell to the HoneyBadger command pod
* Localization
  * English

### Changes 2.0.99.0

### docs/

* Add
  * [`_config.yml`]
  * [Attribution.md] v1.0.7.1
  * [ManualInstallation.md] v1.1.8.0
  * [404.md] v1.0.3.2
  * [LegalMumboJumbo.md] v1.0.5.1
  * [Localizations.md] v1.1.7.0
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * [PartsCatalog.md] v1.1.4.1
  * [Why.md] v1.1.0.0

### Add localized tags to parts

* Add
  * [NearFutureRovers.cfg] v1.0.0.0
    * adds localized tags to parts

### Localization 2.0.99.0

* Create
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
  * closes #14 - English <us-en.cfg>
  * closes #30 - Part Localization
  * updates #13 - Localization - Master

### Part Asset Updates

* create Assets/ folder
* convert
  * from mesh to MODEL {}
  * from .mbm/.tga/.png to .dds
* rename
  * models to unique names
  * textures to unique names
  * remove space and underscores
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate
  * assets to Assets/
  * part.cfg to Parts/
* eliminate
  * duplicate textures
  * duplicate models
* rename parts to standardized names (e.g. nrf-)
* Add
  * <ghostParts.cfg> v2.0.0.0
  * in order to prevent name changes from breaking compatibility

### Compatibility 2.0.99.0

* Add
  * <B9FuelSwitch.cfg> v1.0.0.0
    * disabled by default (no texture switching yet)

### Documentation

* Create
  * GitHub Pages
  * docs/
    * [`_config.yml`]
    * [Attribution.md] v1.0.7.1
    * [ManualInstallation.md] v1.1.8.0
    * [404.md] v1.0.3.2
    * [LegalMumboJumbo.md] v1.0.5.1
    * [Localizations.md] v1.1.7.0
    * [Marketing.md] v1.0.1.0
    * [Notices.md] v1.0.1.0
    * [PartsCatalog.md] v1.1.4.1
    * [Why.md] v1.1.0.0
  * HeroLogo.png
  * copy/convert to HeroLogo.jpg

### Status 2.0.99.0

* Issues
  * closes #9 - Near Future Rovers 2.0.99.0-adoption `<Thank you MichaelV2.0>`
  * closes #10 - 2.0.99.0 Verify Legal Mumbo Jumbo
  * closes #11 - 2.0.99.0 Update Documentation
  * closes #12 - 2.0.99.0 Create Social Media
  * closes #8 - [ImgBot] Optimize images - contributed by imgbot[bot]

---

## Version 2.0.0.0 for Kerbal Space Program 1.3.0

* Released
  * 2017-08-04
  * for Kerbal Space Program 1.3.0

* Added parts
* Honey Badger Rover Cockpit added
* Battery and 1.25m adapter added
* Fuel Switching on tanks to replace multiple different variants of the same tank (texture differences are still present)
* Minor Texture Fixes

### Status 2.0.0.0

* Issues
  * closes #7
  * closes #2 - Previous Releases to Update
  * #35 - Version 2.0.0.0 for Kerbal Space Program 1.3.0 - contributed by zer0Kerbal
  * #2 - Previous Releases to Update
  * #7 - 2.0.0.0 for Kerbal Space Program 1.3.0

---

## Version 1.1.0.0-release `<Archival>` edition

* Released
  * 2016-05-06
  * for Kerbal Space Program 1.2.0

* Resource Update
* large resource containers for ore, Lf/O, Lf and mono propellant
* side containers for ore, Lf/O, Lf and mono propellant
* second crew cabin for easier use of new containers (addition not replacment)
  
### Status 1.1.0.0

* Issues
  * closes #6 - 2.0.0.0 for Kerbal Space Program 1.3.0
  * updates #2 - Previous Releases to Update
  * #34 - Version 1.1.0.0 for Kerbal Space Program 1.2 - contributed by zer0Kerbal
  * #6 - 1.1.0.0 for Kerbal Space Program 1.2

---

## Version 1.0.2.0-release `<Archival>` edition

* Released
  * 2016-04-30
  * for Kerbal Space Program 1.1.2

* Texture fixes on crew cabin and chassis
* will work with 1.1.2
  
### Status 1.0.2.0

* Issues
  * closes #5 - 1.1.0.0 for Kerbal Space Program 1.2.0
  * updates #2 - Previous Releases to Update
  * #33 - Version 1.0.2.0 for Kerbal Space Program 1.1.2 - contributed by zer0Kerbal
  * #5 - 1.0.2.0 for Kerbal Space Program 1.1.2

---

## Version 1.0.1.0-release `<Archival>` edition

* Released
  * 2016-04-30
  * for Kerbal Space Program 1.1.1

* Texture fixes on cargo racks
* Electric charge fix on the cockpit
* Balancing fixes
  
### Status 1.0.1.0

* Issues
  * closes #4 - 1.0.2.0 for Kerbal Space Program 1.1.2
  * updates #2 - Previous Releases to Update
  * #32 - Version 1.0.1.0 for Kerbal Space Program 1.1.1 - contributed by zer0Kerbal
  * #4 - 1.0.1.0 for Kerbal Space Program 1.1.1

---

## Version 1.0.0.0-release `<Archival>` edition

* Released
  * 2016-04-25
  * for Kerbal Space Program 1.1.0

* *No changelog provided*
  
### Status 1.0.0.0

* Issues
  * closes #3 - 1.0.1.0 for Kerbal Space Program 1.1.1
  * updates #2 - Previous Releases to Update
  * #31 - Version 1.0.0.0 - for KSP 1.1.0 [24-Apr-2022] - contributed by zer0Kerbal
  * #3 - 1.0.0.0 for Kerbal Space Program 1.1

---
