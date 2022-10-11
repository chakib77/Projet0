Rapport du projet 0

Nous avons commencé par créer les paquets de 32 et 52 cartes

Code : ![](C:\Users\chaki\Desktop\codeProjet\32cartes.JPG)
       ![](C:\Users\chaki\Desktop\codeProjet\52cartes.JPG)

Ensuite, nous avons demander au joueur si “OUI” ou non, il avait besoin d’aide

Code : ![](C:\Users\chaki\Desktop\codeProjet\aide.JPG)

}

Nous demandons quel paquet le joueur souhaite utiliser. Tant que sa réponse ne correspond pas à l’une des valeurs proposées, la question est reposée

Code : ![](C:\Users\chaki\Desktop\codeProjet\demanderCombien.JPG)
       ![](C:\Users\chaki\Desktop\codeProjet\redemanderCombien.JPG)
       


La partie commence, nous demandons le nom, puis la couleur que le joueur souhaite tenter

Code : ![](C:\Users\chaki\Desktop\codeProjet\partieCommence.JPG)

S’il y a une mauvaise définition des cartes (ou valeur nulle), on l’indique et on propose de réessayer  :

![](C:\Users\chaki\Desktop\codeProjet\mauvaiseDef.JPG)

S’il n’y a pas d’erreur de définition, on regarde si la ”carteDuJoueur” correspond à la carte à deviner

Code : ![](C:\Users\chaki\Desktop\codeProjet\bonneCarte.JPG)
![](C:\Users\chaki\Desktop\codeProjet\carteProposee.JPG)

Si le joueur a deviné la carte, un message s’affiche et le jeu s’arrête

Résultat :  ![](C:\Users\chaki\Desktop\codeProjet\carteTrouvee.JPG)

S’il ne l’a pas trouvé, un message s’affiche ; et on lui indique si sa carte est inférieure ou supérieure à la carte à trouver (S’il a demandé de l’aide) 

Résultat :  ![](C:\Users\chaki\Desktop\codeProjet\carteNonTrouvee.JPG)

La carte a deviner se change à chaque partie lancée :

Code : 

![](C:\Users\chaki\Desktop\codeProjet\Random.JPG)

Voici le diagramme final :

![](C:\Users\chaki\Desktop\codeProjet\diagramme.JPG)