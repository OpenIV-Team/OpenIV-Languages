# OpenIV-Languages
Repository for OpenIV localization files and stuff.

# **This instruction is applied to OpenIV 2.9 and newer.**

## Translate OpenIV
You can translate OpenIV into your native language, this instruction will guide you how to do it.
Also, you can contribute improvements and fixes into existing localizations.

#### Localization files
To get started you need localization files, you can find them in your OpenIV folder:
**C:\Users\[UserName]\AppData\Local\New Technology Studio\Apps\OpenIV\Resources\Languages**

Or in this repository here:
[/master/OpenIV/Resources/Languages](https://github.com/OpenIV-Team/OpenIV-Languages/tree/master/OpenIV/Resources/Languages)

#### Tools
To edit XML files we recommend you to use text editor with syntax highlight. For example [Notepad++](https://notepad-plus-plus.org/).
You can also validate your XML files and check their syntax using Notepad++ XML Tools plugin.

#### Language folder
When you creating your new localization you need to copy **en_GB** folder and correctly name it.
You can find folder name for your language in [this list](https://github.com/OpenIV-Team/OpenIV-Languages/blob/master/LANGUAGES.md).

#### Editing LIP.xml
The LIP.xml file is metadata file that describes your localization pack.
```xml
<?xml version="1.0" encoding="UTF-8"?>
<LanguageInterfacePack version='400' ID='2057' active="true">
	<Contributors>
		<Contributor link="http://openiv.com/">OpenIV Team</Contributor>
	</Contributors>
</LanguageInterfacePack>
```
In this file you need to set correct language ID, you can find ID name for your language in [this list](https://github.com/OpenIV-Team/OpenIV-Languages/blob/master/LANGUAGES.md).

When you edit existing localization, you must add your name into Contributors section of this file.

#### Flag
For the language icon use the country flag. We use PNG images from [this repository](https://github.com/gosquared/flags).
You need to use Flat 32x32 PNG icon, you can find it for your language in [this folder](https://github.com/gosquared/flags/tree/master/flags/flags-iso/flat/32).

#### Constants
In your localization, you can use the following constants:

Constant | Value
-------- | -----
$AppName$ | OpenIV
$ModsFolder$ | "mods"
$ModsFolderPath$ | mods\
$ModsFolderAsi$ | OpenIV.ASI

##### Game specific Constants
The following constants will be different for each game:

Game / Constant | $RageGAME$ | $RageGAME_SHORT$ | $RageGAME_MP$ | $RageEncryptionStorage$ |
-------- | ----- | ------ | ---- | ----------- |
**GTA V** | Grand Theft Auto V | GTA V | GTA Online | GTA5.exe |
**GTA IV** | Grand Theft Auto IV | GTA IV | GTA IV Multiplayer | GTAIV.exe |
**EfLC** | Episodes from Liberty City | EfLC | GTA IV Multiplayer | EFLC.exe |
**Max Payne 3** | Max Payne 3 | Max Payne 3 | Max Payne 3 Multiplayer | MaxPayne3.exe |
**RDR 2** | Red Dead Redemption 2 | RDR 2 | Red Dead Online | RDR2.exe |

#### Changes between OpenIV versions
Every time new OpenIV version released, you probably need to update your localization with new strings and changes. You can find list of changes [here](https://github.com/OpenIV-Team/OpenIV-Languages/commits/Offical-change-log).

#### Submitting your localizations
If you are familiar with GitHub, you can submit your localization right here. If you are not familiar with it, you can send your localizations by contacting us on forums:
* [GTAForums (English)](http://gtaforums.com/forum/403-openiv/)
* [Форумы GTAModding.ru (Русский)]( http://forums.gtamodding.ru/index.php?showforum=47)

## Translate OpenIV Setup
Not yet ready.
