<div align="center">
  <b>⚠️ This project is outdated. Some new Launchers are coming in a few months! ⚠️</b><br>
  <b>⚠️ Ce projet n'est plus maintenu. De nouveaux Launchers arrivent dans quelques mois ! ⚠️</b>
</div><br>

# <p align="center">Arak-Arahm</p>


<p align="center"><img alt=Arak-Arahm Launcher" src="https://user-images.githubusercontent.com/61522145/125778940-72a590d8-ea52-4467-a3e4-926b78248a1b.png" width="800px"></p>

  
[<p align="center"><img src="https://img.shields.io/discord/762253189525012501?color=%235865F2&label=Discord&style=for-the-badge">](https://discord.gg/FePaQ7v)
[<img src="https://img.shields.io/badge/platforms-Windows%2C%20macOS-0077DA?style=for-the-badge&color=0077DA">](#platforms) 
[<img src="https://img.shields.io/badge/version-stable-orangered?style=for-the-badge&color=orangered">](package.json)</p>


### [English description](#en-minecraft-launcher-for-the-modded-server-arak-arahm-french-server)
### [Description française](#fr-launcher-minecraft-pour-le-serveur-modd%C3%A9-arak-arahm-serveur-fran%C3%A7ais)

---

## <span id="platforms">Platform compatibility • Compatibilité des plateformes</span>

| OS (platform) • Système d'exploitation (plateforme) | Supported? • Supporté ?            | Minimum version supported • Version minimale supportée  |
|-----------------------------------------------------|-------------------------------------|---------------------------------------------------------|
| Windows (win32)                                     | Yes • Oui                           | Windows 7 (Windows NT 6.1)                              |
| macOS (Darwin)                                      | Yes • Oui                           | macOS El Capitan (10.11)                                |
| Linux (including Chrome OS • incluant Chrome OS)    | Not officially • Pas officiellement | -                                                       |
| Others • Autres                                     | Not officially • Pas officiellement | -                                                       |

---
  
### [English description](#en-minecraft-launcher-for-the-modded-server-pentagone-ii-french-server)
### [Description française](#fr-launcher-minecraft-pour-le-serveur-modd%C3%A9-pentagone-ii-serveur-fran%C3%A7ais)

##   

## **[EN]** Minecraft Launcher for the modded server "Arak-Arahm" (French server)

### Features :
* Premium Auth (Mojang)
* Minecraft Forge 1.7.10
* Bootstrap
* Java x64 autodownloading (for Windows)
* News (using *[AdminTool](http://minecraft-launcher.medianewsonline.com)* (French website))
* Settings (RAM and Launcher action after launching the Game)
* Medias links
* Slideshow background
* Displaying server information


### Dependencies :
* Font Awesome (`npm install --save @fortawesome/fontawesome-free`)
* Minecraft Launcher Core (`npm i  minecraft-launcher-core` - [documentation](https://github.com/Pierce01/MinecraftLauncher-core))
* Minecraft Server util (`npm i minecraft-server-util` - [documentation](https://github.com/PassTheMayo/minecraft-server-util))
* Axios (`npm i axios`)
* NodeJS File Downloader (`npm i nodejs-file-downloader`) (instead of _HTTP_ and _Request_)
* Decompress (`npm i decompress`) (instead of _Unzipper_)

### Dev Dependencises :
* Electron (`npm i -D electron`)
* Electron Builder (`npm i -D electron-builder`)

### Installation commands

Fisrtly, you must download and install <a href="https://nodejs.org" target="_blank">Node.JS</a>.

##### Clone and install dependencies
```
git clone https://github.com/GoldFrite/ArakArahm_Launcher.git
cd ArakArahm_Launcher
npm i
```

##### Start application in test
```
npm run test
```

##### Build application
| Plateforme          | Commande                    |
|---------------------|-----------------------------|
| Windows (win32)     | `npm run buildWin`          |
| macOS (Darwin)      | `npm run buildMac`          |
| Linux Distributions | not supported at the moment |

### Warning !

This Launcher is based on another Launcher that I created, but this last one is not available on GitHub.

This Launcher is under *GNU AGPLv3* licence, so you can clone it for your own project. For more informations, please check the *LICENSE* file.

---

## [FR] Launcher Minecraft pour le serveur moddé "Arak-Arahm" (serveur français)

### Caracteristiques :
* Authentification Premium (Mojang)
* Minecraft Forge 1.7.10
* Mises à jour automatiques du Launcher
* Téléchangement automatique de Java x64 (pour Windows)
* News (utilisant *[AdminTool](http://minecraft-launcher.medianewsonline.com)* (site français))
* Paramètres (RAM et Action du Launcher après le lancement du Jeu)
* Liens réseaux sociaux
* Fond d'écran diaporama
* Affichage des infosmations du serveur

### Dépendences :
* Font Awesome (`npm install --save @fortawesome/fontawesome-free`)
* Minecraft Launcher Core (`npm i  minecraft-launcher-core` - [documentation](https://github.com/Pierce01/MinecraftLauncher-core))
* Minecraft Server util (`npm i minecraft-server-util` - [documentation](https://github.com/PassTheMayo/minecraft-server-util))
* Axios (`npm i axios`)
* NodeJS File Downloader (`npm i nodejs-file-downloader`) (à la place de _HTTP_ et _Request_)
* Decompress (`npm i decompress`) (à la place de _Unzipper_)
  
### Dépendences de dev :
* Electron (`npm i -D electron`)
* Electron Builder (`npm i -D electron-builder`)
  
### Commandes d'installation

Pour commencer, vous tevez télécharger et installer <a href="https://nodejs.org/fr/" target="_blank">Node.JS</a>.

##### Cloner puis installer les dépendances
```
git clone https://github.com/GoldFrite/ArakArahm_Launcher.git
cd ArakArahm
npm i
```

##### Lancer l'application en test
```
npm run test
```

##### Exporter l'application (build)
| Plateforme          | Commande                    |
|---------------------|-----------------------------|
| Windows (win32)     | `npm run buildWin`          |
| macOS (Darwin)      | `npm run buildMac`          |
| Distributions Linux | non supporté pour le moment |

### Attention !

Ce Launcher est basé sur un autre Launcher que j'ai créé, mais ce dernier n'est pas disponible sur GitHub.

Ce Launcher est sous licence *GNU AGPLv3*. Vous pouvez donc cloner ce Launcher pour créer le votre. Pour plus d'informations, veuillez lire le fichier *LICENSE*.
