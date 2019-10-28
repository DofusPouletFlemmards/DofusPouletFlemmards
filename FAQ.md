
## FAQ

[ [ACCUEIL](README.md) ]  

#### [1. Pour quelle version de Dofus ?](#nr1) ####

> 1.29 et RETRO en 32bit 

#### [2. DofusPouletFlemmards, pour quel système d'exploitation ?](#nr1) ####

> Windows seulement, AHK n'existe pas sur MAC


#### [3. Mon PC à du mal a tourner X Dofus, puis je faire tourner DofusPouletFlemmards ?](#nr1) ####

> Déconseillé, certaines fonctions ne marcheront pas correctement dans le sens où son comportement sera irrégulier. 
> Par exemple, si vous avez 8 personnages et que vous utilisez Auto Move seulement 7 personnages bougeront puis parfois 8 bougeront puis 6...    
  
> Auto Move/Ready/Join/Escape seront frustrant à utiliser, vous allez devoir retourner sur le personnage qui n'a pas bougé, ou qui ne s'est pas mis prêt etc. en spammant sur la touche qui permet de basculer entre les fenêtres Dofus pour retrouver ce fichu personnage 
> Vous pouvez toujours ralentir le fonctionnement de chaque fonction, mais au-delà d'un certain temps (1000ms)... autant le faire manuellement ! 
  
> Vous pouvez normalement utiliser l'auto Switch sans aucun problème, vous pouvez le laisser activer pendant toute votre session de jeu si vous n'avez pas de soucis sinon désactiver à la fin de chaque combat .   
> DofusPouletFlemmards tourne à 0% d'utilisation du CPU et entre 0 à 5% lorsque l'auto switch est activé.    
>(Plus le délai d'Auto Switch est faible, plus l'utilisation du CPU est élevée) 

#### [3. Est-ce que j'ai accès a vos comptes ?](#nr1) ####

> NON !!! 
> DofusPouletFlemmards simule les fonctions de la souris, saisie du texte et detecte les images (captures d'écran des noms de votre personnage pour l'auto switch) 

#### [4. Où sont stocké les comptes ?](#nr1) ####

> Au premier lancement du programme, un dossier DofusPourLesFlemmards sera créé dans vos Documents      
> Le dossier DofusPouletFlemmards contiendra :
> * un fichier **accounts.txt** pour stocker vos comptes.
> * Un fichier **settings.ini** pour stocker vos configurations ( raccourcis, délais)
> * Un dossier **screenshot** pour stocker les captures d'écran contenant le nom de vos personnages (pour l'Auto Switch)

#### [5. Pourquoi mon discord se redemarre lorsque j'appuie sur Start pour me connecter automatiquement ?](#nr1) ####

> Je ne sais pas ! C'est un problème qui me rend fou, je n'ai jamais rencontré ce problème mais pour certaines personnes ça redemarre.    
> Sinon, ça ne devrait pas poser de problème sur le fonctionnement d'Auto Log In .. si y a un problème quitter discord avant d'utiliser l'auto log in  
> Je suis désolé !   
> Comment est-ce que ce bout de code fait redémarrer Discord ???

```
  StartDofus(){
        Run % DofusPath
        Sleep, 200
  }
```
> Si quelqu'un a une idée, je suis preneur ... Bah sinon, je rejette la faute sur Discord ge sui 1 tr bon programr (ou pas)
