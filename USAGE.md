

# CONFIGURATION

[ [ACCUEIL](README.md) ] - [LES RACCOURCIS](#raccourcis) ] - [ [AUTO LOG IN](#autologin) ] - [ [PAIRING](#pairing) ] - [ [AUTO SWITCH](#autoswitch) ] - 
[ [AUTO READY](#autoready) ] -  [ [TIPS](#tips) ] 

### Les raccourcis<a name="raccourcis"></a>

Vous pouvez modifier les raccourcis par défaut sur DofusPouletFlemmards.
Il n'est pas possible d'ajouter les fonctions de la souris (Clic, molette) depuis l'interface graphique, il faut éditer le fichier directement.


- Ouvrir **DofusPouletFlemmards**, catégorie **AUTO**
- **EDIT FILE**
- Rechercher la fonction que vous souhaitez changer dans AUTO et saisir la combinaison de touche que vous voulez
- Et relancer le programme ( par défaut : Alt + & ou quitter et relancer)

**Exemple**

| CTRL + CLIC GAUCHE                 	| ALT + CLIC GAUCHE                  	| Molette haut        	|
|------------------------------------	|------------------------------------	|---------------------	|
| AutoMoveKey=^LButton               	| AutoMoveKey=!LButton               	| AutoMoveKey=WheelUp 	|
| ^ : CTRL                           	| ! : ALT                            	|                     	|
| LButton : Clic gauche de la souris 	| LButton : Clic gauche de la souris 	|                     	|

Sur DofusPouletFlemmards, la combinaison apparaitra comme " Ctrl + " mais ne vous inquiétez pas, la fonction est bien définie pour Ctrl + Clic ou molette 

Pour plus d'information sur les raccourcis voir :   
https://www.autohotkey.com/docs/Hotkeys.htm  
https://www.autohotkey.com/docs/KeyList.htm#mouse-general  

/!\ Je déconseille CTRL + Clic comme raccourci, sur Dofus Ctrl+Clic vous permet de transférer un stack d'item.
Vous pouvez utilisez CTRL + Clic si et seulement si vous comptez utiliser l'auto CtrlClicker ce que je fais personnellement (par défaut : Alt+C)


### Auto Log In<a name="autologin"></a>

> /!\ Si vous n'utilisez pas l'auto Log In pour vous connectez et que vous utilisez le launcher Ankama      
>Vérifier que Dofus est en 32bits, DofusPouletFlemmards ne marche pas sur la version 64bit 

Si vous avez une installation autre que celle par défaut
- Appuyez sur le bouton Start, il vous sera demandé d'ouvrir le fichier Dofus.exe qui est situé dans votre dossier d'installation :
>...\Ankama\zaap\retro\resources\app.asar.unpacked\retroclient

**Comment ajouter un compte ?**
- Inscrivez votre identifiant et mot de passe puis appuyez sur le bouton ADD
- Si vous avez le même mot de passe pour tous vos comptes, vous pouvez éditer directement le fichier en cliquant sur le bouton "Edit File"

Votre fichier doit être de ce format-là :

>identifiant:mdp   
>identifiant:mdp   
>identifiant:mdp  

_**(OPTIONNEL)**_ Pour faciliter la tâche, cochez " Keep Gui on top" cela permettra de garder DofusPouletFlemmards toujours au-dessus de n'importe quelle fenêtre 

___

### Pairing -> IMPORTANT si vous souhaitez utiliser AutoSwitch et Invite <a name="pairing"></a>

- Sur DofusPouletFlemmards : Appuyez sur le bouton Chat Pos [(X,Y)] et cliquer sur n'importe quel endroit du chat Dofus

![1](https://i.imgur.com/WabGtYn.png)

### Auto Switch<a name="autoswitch"></a>

- Connectez tous vos personnages, lancez un défi et rejoignez avec tout vos personnages

**1re étape :**
- Sur DofusPouletFlemmards : Cliquer sur le bouton (X1,Y1) et cliquer en haut à gauche du nom de votre personnage affiché sur l'illustration en début tour.
- Cliquer sur le bouton (X2,Y2) et cliquer en bas à droite du nom de votre personnage affiché sur l'illustration en début de tour.

![1](https://i.imgur.com/Qxqme01.png)

**2e étape :** 

Pour prendre une capture d'écran : 
Touche **Impr Écran** OU disponible seulement sur Windows 10 : **Win+Shift+S**

Toujours en défi avec TOUS vos personnages:  
Avec **Win+Shift+S**
- Appuyez sur _**Win+Shift+S**_ lors de l'apparition de l'illustration en début de tour et capturez la zone contenant le nom
- Ouvrez Paint ( touche Win puis saisir Paint) 
- _**CTRL-V**_ pour coller
- Puis cliquer sur "rogner" ou "crop"
- Enregistrer l'image dans **\Documents\DofusPourLesFlemmards\Screenshots**, le nom de l'image doit être **identique** au nom de votre personnage. 
- Répéter la manipulation pour tous les personnages

___

Avec **Impr Ecran**
- Appuyez sur _**Impr Ecran**_ lors de l'apparition de l'illustration en début de tour et capturez la zone contenant le nom
- Ouvrez Paint ( touche Win puis saisir Paint) 
- _**CTRL-V**_ pour coller
- Puis sélectionnez la zone contenant le nom avec la forme rectangulaire et cliquez sur "rogner" ou "crop"
- Enregistrer l'image dans **\Documents\DofusPourLesFlemmards\Screenshots**, le nom de l'image doit être **identique** au nom de votre personnage. 
- Répeter la manipulation pour tous les personnages

___

### Auto Ready<a name="autoready"></a>

- Lancez un défi, ou combat
- Sur DofusPouletFlemmards : Appuyez sur le bouton Ready [(X,Y)] et cliquer sur le bouton Ready de Dofus

![1](https://i.imgur.com/ue8pKTs.png)

**/!\ En défi, la position du bouton Prêt correspond au bouton "Annuler"**

___

### L'HIVER APPROCHE, COMMENT GARDER UNE MAIN AU CHAUD SOUS LES FESSES <a name="tips"></a>

Si vous avez une souris avec des boutons programmables, attribuez chaque fonction à un bouton.

![1](https://imgur.com/Fsgapak.png)

