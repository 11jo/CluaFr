CluaFr
version 1.2



Traduction des CheatsAreas (Zones du jeu accessibles grâce à la CLUA console)

Pour BGEE, BGSoD, BG2EE et EET. Également compatible avec IWDEE.


Compatibilité :
----------------


- Si vous prévoyez d'installer EET, Installez ce mod après EET


- Installer ce mod après Check the bodies, Trials of the Luremaster et Test Your Mettle


- Il est préférable d'installer CluaFr après les mods qui ajoutent de nouvelles zones à la CluaConsole, ceux-ci peuvent se baser sur les nom anglais pour s'insérer dans le jeu.


- Il est préférable d'installer CluaFr après les mods d'interface (UI) 


- Pour utiliser la CLUAConsole le Debug Mode doit être activé à l'aide de l'un des mods ci-dessous.


Reveal Hidden Gameplay Options

EEUITweaks


- Ou bien manuellement !
  
Pour les Enhanced Editions, il faut se rendre dans Mes Documents, le répertoire ou se situe les "save" du jeu. (nommé "Baldur's Gate - Enhanced Edition", "Baldur's Gate II - Enhanced Edition" ou "Baldur's Gate - Enhanced Edition Trilogy" pour EET)

Dans le fichier Baldur.lua ajoutez la ligne suivante en dessous de n'importe quelle ligne similaire :

    SetPrivateProfileString('Program Options','Debug Mode','1')


Composants :
---------------


 1. Areas Cheats


- Choix 1 : Traduit en français les noms des cartes du jeu accessible dans la CLUAConsole

- Choix 2 : Traduit en français les noms des cartes du jeu accessible dans la CLUAConsole et Ajoute l'accès aux extensions pendant la campagne principale. 
	- Donne acces aux Fosses noires et au tutoriel dans BGEE et BGEE
	- Donne acces aux zones de Siege Of Dragonspear dans BGEESoD et aux zones de ToB dans BG2EE
	- Pour Icewind Dale ce sera Heart of Winter et Trials of the Lurmaster
	- Ajoute une séparation entre les campagnes

 2. Areas Cheats pour MODS

Traduit en français les noms des cartes ajoutées par des mods dans la CLUAConsole

Ce composant détecte automatiquement si certains mods sont installés...

Mods supportés :

- Check the bodies

- Trials of the Luremaster
 
- Test Your Mettle
 
- IWD1_EET

Mods "bientôt" supportés :

- IWD2_EET
 

Installation :
--------------


Extraire l'archive dans le répertoire du jeu et lancer Setup-CluaFr.exe, puis suivre les indications.


Remerciement :
----------------


Un grand merci à Selphira  !


Version History :
----------------


v1.0 : 

- Initial release

v1.1

- BWS-FR-Fixpack detection update for new version

V1.2

- Cleanup and Typos in tp2
- Uniformisation
- Delete Unused folder