# CluaFr


![Language](https://img.shields.io/static/v1?label=language&message=french%20%7C%20&color=informational)

**Auteur** : ****


## Description :
---------------


Traduction des CheatsAreas (Zones du jeu accessibles grâce à la CLUA console)

Pour BGEE, BGSoD, BG2EE et EET. Également compatible avec IWDEE.


- **Si vous prévoyez d'installer EET, Installez ce mod après EET**


- **Installer ce mod après Check the bodies, Trials of the Luremaster et Test Your Mettle**


- **Il est préférable d'installer CluaFr après les mods qui ajoutent de nouvelles zones à la CluaConsole, ceux-ci peuvent se baser sur les nom anglais pour s'insérer dans le jeu.**


- **Il est préférable d'installer CluaFr après les mods d'interface (UI)** 


- **Pour utiliser la CLUAConsole le Debug Mode doit être activé à l'aide de l'un des mods ci-dessous.**


[Reveal Hidden Gameplay Options](https://github.com/Argent77/A7-HiddenGameplayOptions/releases)

[EEUITweaks ](https://github.com/r-e-d/EEUITweaks/releases)


- **Ou bien manuellement !**
  
Pour les Enhanced Editions, il faut se rendre dans **Mes Documents**, le répertoire ou se situe les "save" du jeu. (nommé "Baldur's Gate - Enhanced Edition", "Baldur's Gate II - Enhanced Edition" ou "Baldur's Gate - Enhanced Edition Trilogy" pour EET)

Dans le fichier **Baldur.lua** ajoutez la ligne suivante en dessous de n'importe quelle ligne similaire :

    SetPrivateProfileString('Program Options','Debug Mode','1')


## Composants :
---------------

### Areas Cheats


#### Choix 1 : Traduit en français les noms des cartes du jeu accessible dans la CLUAConsole

<details>
  <summary>Aperçu choix 1</summary>

![BGSoD](https://11jo.github.io/L-P-T/Pictures/CluaFR/BGEECLUAFR01.png)
![BGSoD](https://11jo.github.io/L-P-T/Pictures/CluaFR/BGEECLUAFR02.png)
![BG2EE](https://11jo.github.io/L-P-T/Pictures/CluaFR/BG2EECLUAFR01.png)
 
</details>



#### Choix 2 : Ajoute l'accès aux extensions pendant la campagne principale. 
	- Donne acces aux Fosses noires et au tutoriel dans BGEE et BGEE
	- Donne acces aux zones de Siege Of Dragonspear dans BGEESoD et aux zones de ToB dans BG2EE
	- Pour Icewind Dale ce sera Heart of Winter et Trials of the Lurmaster
	- Ajoute une séparation entre les campagnes, voir aperçu ci-dessous

<details>
  <summary>Aperçu choix 2</summary>

![BGSoD](https://11jo.github.io/L-P-T/Pictures/CluaFR/BGEECLUAFR10.png)
![BGSoD](https://11jo.github.io/L-P-T/Pictures/CluaFR/BGEECLUAFR11.png)
![BG2EE](https://11jo.github.io/L-P-T/Pictures/CluaFR/BG2EECLUAFR10.png)
 
</details>



### Areas Cheats pour MODS


Traduit en français les noms des cartes ajoutées par des mods dans la CLUAConsole

<details>
  <summary>Aperçu pour les mods</summary>

![Mod](https://11jo.github.io/L-P-T/Pictures/CluaFR/MODSCLUAFR01.png)
![Mod](https://11jo.github.io/L-P-T/Pictures/CluaFR/MODSCLUAFR02.png)
 
</details>

Ce composant détecte automatiquement si certains mods sont installés...


<details>
  <summary>Liste des mods concernés</summary>

Mods supportés :

- Check the bodies

- Trials of the Luremaster
 
- Test Your Mettle
 
- IWD1_EET

Mods **bientôt** supportés :

- IWD2_EET
 
</details>


## Installation :
----------------


Extraire l'archive dans le répertoire du jeu et lancer Setup-CluaFr.exe, puis suivre les indications.


## Compatibilité :
----------------


CluaFr devrait être installé après les mods qui ajoutent des nouvelles cartes et peuvent se baser sur les nom anglais pour s'insérer dans la CLUAConsole.



Pour le composant Areas Cheats pour MODS, celui-ci doit s'installer impérativement après les mods qui ajoutent des nouvelles cartes afin de les intégrer lui même à la CLUAConsole. (Voir la liste des mods concernés)


## Remerciement :
----------------


Un grand merci à Selphira  !


## Version History :
----------------


v1.0 : 

- Initial release

v1.1

- BWS-FR-Fixpack detection update for new version

V1.2

- Cleanup and Typos in tp2
