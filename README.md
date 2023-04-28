# GUIDE D'UTILISATION D'EDU TOOL :  

Set-up nécessaire :
-----------------
D'abord, il faudra récupérer le fichier partage ci-joint, dans lequel se trouve les dossiers nécessaires au fonctionnement de l'application, et le placer dans un dossier accessible à tous ( ressources partagées ).

Ensuite, il faudra modifier les chemins à l'interieur du code de ET_Prof VF et ET_Partage VF :
  - chemin_partage="E:/xemple/de/chemin/"
  - prof="E:/xemple/de/chemin/prof.txt"

Puis, il faudra compléter le fichier prof.txt avec la listes des identifiants de professeurs, séparés par des retours à la ligne.

Fichiers classe :
-----------------
Les fichiers classes, contiennent la liste des identifiants des élèves d'une classe, ainsi que celui du professeur qui s'en occupe, et ce selon le modèle suivant :

>id_prof  
>  
>id_eleve1  
id_eleve2  
id_eleve3  
id_eleve4  
id_eleve5  

soit l'identifiant du professeur, suivi d'une ligne sauté, suivie de la liste des identifiants des élèves séparés de retour à la ligne, il n'y a pas de limite d'élèves dans une classe, cependant une liste trop longue pourrait ralentir le programme. Les fichiers classes devront se sittuer dans un dossier à disposition des élèves.
  
Utilisation :
-----------------
1) L'élève :  
Lors du lancement du programme, si il n'est ciblé par aucun partage, alors "Aucun Partage en Cours" s'affichera, dans me cas échéant apparaitront les icones des fichiers partagées par le professeur, et l'élève pourra y accéder en cliquant dessus. Si un QCM  à été mis à disposition par le professeur alors la fenêtre du QCM apparaitra et il pourras y répondre une fois son nom et prénom renseigné.

2) Le professeur :  
Lorsque le proffeseur souhaite partager un ou plusieurs fichiers à ses élèves, il doit les séléctionner un par un en cliquant sur le bouton *"Télécharger un fichier"*,
il peut ensuite donner un titre à son partage dans le champs de texte prévu à cette effet, et enfin il doit choisir la classe auquel béneficiera ce partage en cliquant sur le bouton *"Destinataire du partage"* ce qui lui ouvrera une fenêtre ou il devra sélectionner le fichier classe ( selon les dispositions exposés en 2 ). Cela debloquera alors le bouton *"Envoyer les fichiers"*.   

![imagepartag](https://github.com/chauletr/test/blob/main/partage.png)  
  
Lorsque le professeur souhaite créer un QCM, il doit d'abord cliquer sur le bouton *"Créer un Nouveau QCM"*, ce qui lui ouvrira une fenetre dans lequel il devra ajouter des questions, des choix, les bonnes réponses serons listés à la suite, exemple ci dessous. Une fois fini, il devra cliquer sur le bouton *"Sauvegarder"* et une fenêtre s'ouvrira pour lui proposer ou enregistrer le fichier. Le QCM sera nommée "QCM nom_du_qcm.txt", les reponses quant à elles, "QCM nom_du_qcm co.txt".  

`/!\ Il faut veiller à garder les réponses dans le même dossier que le QCM /!\`

![imageqcmcre](https://github.com/chauletr/test/blob/main/qcm!creation.png)

Lorsque le proffeseur souhaite partager un QCM à ses élèves, il doit le séléctionner en cliquant sur le bouton *"Télécharger un QCM"*, il doit choisir la classe auquel béneficiera ce QCM en cliquant sur le bouton *"Selectionner les élèves"* ce qui lui ouvrera une fenêtre ou il devra sélectionner le fichier classe ( selon les dispositions exposés en 2 ). Cela debloquera alors le bouton *"Commencer le QCM"*. Une fois le QCM commencé le professeur pourra cliquer sur le bouton *"Raffraichir les réponses "* pour que s'actualise un tableau avec les réponses de chaques élèves ainsi que leurs note /20.  

![imageqcm](https://github.com/chauletr/test/blob/main/qcm.png)
