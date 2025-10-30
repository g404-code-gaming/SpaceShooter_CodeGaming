# 3 Programmation des dangers

Dans le jeu, il y aura deux types principaux de danger : 

   - Les météores, qui avancent en ligne droite.
   - Les vaisseaux ennemis (ou aliens), qui se dirigent vers le joueur.

## Déplacement des ennemis

Nous allons programmer le déplacement des ennemis.

Maintenant, on va simplement ajouter une action de déplacement vers le vaisseau. Ajoute une action qui déplace l'ennemi vers le vaisseau avec une vitesse de ton choix.

![deplacement-ennemi](https://github.com/g404-code-gaming/SpaceShooter_CodeGaming/blob/main/instructions/images/3_ennemimove.JPG)

## Apparition des météores

On va corser un peu les choses en ajoutant des météores qui vont venir de la droite de l'écran. Nous allons utiliser un outil plus complexe qu'une simple condition cette fois. Nous allons utiliser les **Chronomètres** ! 

En effet, on souhaite que les Météores apparaissent tout le temps à intervalle régulier. Un chronomètre permettra de compter le temps et faire apparaître périodiquement des météores.

Commencez par créer un évènement qui initie le chronomètre au lancement de la scène

![image 0](https://github.com/g404-code-gaming/SpaceShooter_CodeGaming/blob/main/instructions/images/4_meteor_1.JPG)

Ensuite, il faut programmer l'apparition des Météores : 

(1) Ils apparaissent lorsque la valeur du chronomètre dépasse 0.5 seconde. 
(2) Cela crée un météore à une position aléatoire sur la droite de l'écran 
(3) Le météore est ensuite déplacée vers la gauche à l'aide d'une force. 
(4) Pour être certain que le météore ait la bonne taille, ont l'aggrandie. 

![image 0](https://github.com/g404-code-gaming/SpaceShooter_CodeGaming/blob/main/instructions/images/4_meteor_2.JPG)


C'est partis pour la suite : [Polissage et finalisation](04_polissage.md) 🎉
