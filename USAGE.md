

# CONFIGURATION

[ [HOME](README.md) ] - [ [AUTO LOG IN](#autologin) ] - [ [SHORTCUTS](#raccourcis) ]  - [ [PAIRING](#pairing) ] - [ [AUTO SWITCH](#autoswitch) ] - 
[ [AUTO READY](#autoready) ] -  [ [AUTO SKIP](#autoskip) ] - [ [AUTO BUFF(CUPI/CHANCE)](#autobuff) ] - [ [AUTO BUFF - COFFRE ANIME ](#chest)] - [ [1 touche 1 personnage + Bip sonore](#onekey) ] - [ [TIPS](#tips) ] 

## Auto Log In<a name="autologin"></a>

> /!\ Si vous n'utilisez pas l'auto Log In pour vous connectez et que vous utilisez le launcher Ankama      
>Vérifier que Dofus est en 32bits, DofusPouletFlemmards ne marche pas sur la version 64bit 

Si vous avez une installation autre que celle par défaut
- Appuyez sur le bouton Start, il vous sera demandé d'ouvrir le fichier Dofus.exe qui est situé dans votre dossier d'installation :
>...\Ankama\zaap\retro\resources\app.asar.unpacked\retroclient

- EHH T'AS BIEN TOUT LU J'ESPERE??? ATTENTION A LA GIRAFE

**Comment ajouter un compte ?**
- Inscrivez votre identifiant et mot de passe puis appuyez sur le bouton ADD
- Si vous avez le même mot de passe pour tous vos comptes, vous pouvez éditer directement le fichier en cliquant sur le bouton "Edit File"
- Sauvegardez le fichier et relancer le programme ( par défaut : ALT + &)

Votre fichier doit être de ce format-là :

>identifiant:mdp   
>identifiant:mdp   
>identifiant:mdp  

- EHH T'AS BIEN TOUT LU J'ESPERE??? ATTENTION A LA GIRAFE
___

## Les raccourcis<a name="raccourcis"></a>

Vous pouvez modifier les raccourcis par défaut sur DofusPouletFlemmards.
Il n'est pas possible d'ajouter les fonctions de la souris (Clic, molette) ou la touche TAB depuis l'interface DFP, il faut éditer le fichier.


- Ouvrir **DofusPouletFlemmards**, catégorie **AUTO**
- **EDIT FILE**
- Rechercher la fonction que vous souhaitez changer dans [AUTO] et attribuer la combinaison de touche que vous voulez
- Et relancer le programme ( par défaut : Alt + & ou quitter et relancer)
- EHH T'AS BIEN TOUT LU J'ESPERE??? ATTENTION A LA GIRAFE

**Exemple AutoMoveKey**

| CTRL + CLIC GAUCHE                 	| ALT + CLIC GAUCHE                  	| Molette haut        	|
|------------------------------------	|------------------------------------	|---------------------	|
| AutoMoveKey=^LButton               	| AutoMoveKey=!LButton               	| AutoMoveKey=WheelUp 	|
| ^ : CTRL                           	| ! : ALT                            	|                     	|
| LButton : Clic gauche de la souris 	| LButton : Clic gauche de la souris 	|                     	|

Sur DofusPouletFlemmards, la combinaison apparaitra comme " Ctrl + " mais ne vous inquiétez pas, la fonction est bien définie pour Ctrl + Clic ou molette 

**Exemple 2 - Switch Tab**<a name="tab"></a>

| TAB                	| 
|------------------------------------	|
| SwitchTabKey=TAB               	|


Pour plus d'information sur les raccourcis voir :   
https://www.autohotkey.com/docs/Hotkeys.htm  
https://www.autohotkey.com/docs/KeyList.htm#mouse-general  

> /!\ Je déconseille CTRL + Clic comme raccourci, sur Dofus Ctrl+Clic vous permet de transférer un stack d'item.
Vous pouvez utilisez CTRL + Clic si et seulement si vous comptez utiliser l'auto CtrlClicker ce que je fais personnellement (par défaut : Alt+C)

- - EHH T'AS BIEN TOUT LU J'ESPERE??? ATTENTION A LA GIRAFE

## Pairing -> IMPORTANT si vous souhaitez utiliser AutoSwitch et Invite <a name="pairing"></a>

Il est possible de faire Pairing de deux manières : 

**1re façon - Pairing automatique via l'auto log in :**

- Sur DofusPouletFlemmards, dans "Accounts"
- Appuyez sur le bouton "Link Char" situé tout en bas
- Saissisez le nom de vos personnages correspond au compte
- Appuyez sur le bouton save
- EHH T'AS BIEN TOUT LU J'ESPERE??? ATTENTION A LA GIRAFE

![1](https://i.imgur.com/5tynqq2.png)

**2ème façon - Pairing semi automatique en jeu :**
- Sur DofusPouletFlemmards : Appuyez sur le bouton Chat Pos [(X,Y)] et cliquer sur n'importe quel endroit du chat Dofus
- Vous devez avoir le chat VERT activé sur tous les personnages.
- EHH T'AS BIEN TOUT LU J'ESPERE??? ATTENTION A LA GIRAFE

![1](https://i.imgur.com/WabGtYn.png)

___

## Auto Switch<a name="autoswitch"></a> ou en VIDEO >[CLICK ICI !](https://www.youtube.com/watch?v=C-uG38r7FlI)<

- Connectez tous vos personnages, lancez un défi et rejoignez avec tout vos personnages
- EHH T'AS BIEN TOUT LU J'ESPERE??? ATTENTION A LA GIRAFE

**1re étape :**

_**(OPTIONNEL)**_ Pour configurer les positions (X1,Y1) et (X2,Y2) , cochez " Keep Gui on top" cela permettra de garder DofusPouletFlemmards toujours au-dessus de n'importe quelle fenêtre.

- Sur DofusPouletFlemmards : Cliquer sur le bouton (X1,Y1) et cliquer en haut à gauche du nom de votre personnage affiché sur l'illustration en début tour.
- Cliquer sur le bouton (X2,Y2) et cliquer en bas à droite du nom de votre personnage affiché sur l'illustration en début de tour.
- A FAIRE QU'UNE SEULE FOIS !
- EHH T'AS BIEN TOUT LU J'ESPERE??? ATTENTION A LA GIRAFE

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
- Votre capture doit ressembler à ceci :
![1](https://i.imgur.com/eBwsuZX.png)


___

Avec **Impr Ecran**
- Appuyez sur _**Impr Ecran**_ lors de l'apparition de l'illustration en début de tour et capturez la zone contenant le nom
- Ouvrez Paint ( touche Win puis saisir Paint) 
- _**CTRL-V**_ pour coller
- Puis sélectionnez la zone contenant le nom avec la forme rectangulaire et cliquez sur "rogner" ou "crop"
- Enregistrer l'image dans **\Documents\DofusPourLesFlemmards\Screenshots**, le nom de l'image doit être **identique** au nom de votre personnage. 
- Répeter la manipulation pour tous les personnages
- EHH T'AS BIEN TOUT LU J'ESPERE??? ATTENTION A LA GIRAFE

___

## Auto Ready<a name="autoready"></a>

- Lancez un défi, ou combat
- Sur DofusPouletFlemmards : Appuyez sur le bouton Ready [(X,Y)] et cliquer sur le bouton Ready de Dofus
- EHH T'AS BIEN TOUT LU J'ESPERE??? ATTENTION A LA GIRAFE

![1](https://i.imgur.com/ue8pKTs.png)

**/!\ En défi, la position du bouton Prêt correspond au bouton "Annuler"**

### Auto Skip<a name="autoskip"></a>

- Attribuez **Skip Key** à la touche que vous avez pour skip sur Dofus
- EHH T'AS BIEN TOUT LU J'ESPERE??? ATTENTION A LA GIRAFE

![1](https://i.imgur.com/yigvyog.png)

___

## Auto Buff ( Cupidité / Chance )<a name="autobuff"></a>

- Allez dans "Auto Buff"
- Configure les positions comme ceci
- N'oubliez pas de configurer les touches sur le programme et sur Dofus !
- EHH T'AS BIEN TOUT LU J'ESPERE??? ATTENTION A LA GIRAFE

![1](https://i.imgur.com/zMmBeEF.png)

## AUTO Buff ( Coffre Ani. ) <a name="chest"></a>

- Allez dans "Auto Buff" -> CHEST 
- Configurez les positions (X1,Y1) et (X2,Y2) comme ceci

![1](https://i.imgur.com/AHjjBZZ.png)

- N'oubliez pas de configurer les touches sur le programme et sur Dofus ! 
   * Chest Key : Touche de raccourci correspondant au coffre animé
   * AnySpell Key : Doit être un sort possèdant 1 de portée et qui peut être relancer chaque tour ou soyez sur que vous ne l'utiliserez pas avant le coffre animé !! (CAC/Pelle Animée/Sac Animée etc...)
   
 
- Allez dans Option et activez " **Mettre en valeur les cases ciblables** "
- EHH T'AS BIEN TOUT LU J'ESPERE??? ATTENTION A LA GIRAFE

![1](https://i.imgur.com/pPmUlFD.png)

___

## 1 touche 1 personnage + Bip sonore <a name="onekey"></a>

- Une fois le pairing effectué
- Cliquez sur le bouton "Chicken Factory"
- Associez la touche que vous souhaitez à un personnage
- (OPTIONNEL) Bip sonore lors du tour du personnage.
- Appuyez sur Save
- EHH T'AS BIEN TOUT LU J'ESPERE??? ATTENTION A LA GIRAFE

![1](https://i.imgur.com/k4BafzK.png)

___
### L'HIVER APPROCHE...  <a name="tips"></a>
### COMMENT GARDER UNE MAIN AU CHAUD SOUS LES FESSES TOUT EN JOUANT HIHI 

Si vous avez une souris avec des boutons programmables, attribuez chaque fonction à un bouton.  

Exemple pour la G502 :
![1](https://imgur.com/Fsgapak.png)

