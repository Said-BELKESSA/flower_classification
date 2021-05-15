# flower_classification
Projet Reconnaissance d’Image

Ce travail est fait par Tala, Immel Yameogo, Kea et moi même Belkassa Said

Exercice en classe de Deep Learning :

1/- Créer repo Github contenant :
* Readme avec le contexte de la compétition, les données et les difficultés rencontrées
* Notebook commenté
* Noter les "astuces"
Compétion choisie : https://www.kaggle.com/nachiket273/flower-classification-lookahead-radam

2/- Données et contexte compétition:
Cette compétition a été créée par Udacity pour avoir un classement ( officieux ) du Udacity PyTorch FB Challenge. Nous avons un dataset consistant de 102 categories de fleurs differentes. Nous avons :

* Dossier train contenant 102 dossiers pour chacune des classes de fleurs. Chaque dossier a entre 40 et 258 images
* Dossier valid contenant 102 dossiers pour chacune des classes de fleurs
* Dossier test contenant 819 images pour la submission de la compétition
* Fichier cat_to_name.json avec comme clé le numéro du dossier/classe et comme valeur le nom de la classe/fleur

3/- Astuces:
* Cyclic Learning Rate ( CLR ) https://arxiv.org/abs/1506.01186
* ![image](https://user-images.githubusercontent.com/57968291/118370100-6cd48e00-b5a6-11eb-8a92-9ca44ba07d3d.png)
