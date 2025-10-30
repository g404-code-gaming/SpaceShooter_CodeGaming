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

## Ajout des power-ups

Nous allons donner la possibilité au joueur de récupérer des power-ups qui vont lui donner des bonus. Nous allons utiliser la variable "powerUp" du vaisseau.

1. Ajoute une condition qui vérifie si le vaisseau du joueur est en collision avec un power-up. Si c'est le cas, ajoute une action qui supprime le power-up et qui met la variable "powerUp" du vaisseau du joueur à true. Au bout de 10 secondes, ajoute une action qui met la variable "powerUp" du vaisseau du joueur à false.

![power up](https://github.com/g404-code-gaming/SpaceShooter_CodeGaming/blob/main/instructions/images/4_powerup_1.JPG)

3. Il va falloir modifier le comportement du vaisseau du joueur pour qu'il tire des projectiles plus puissants quand il a un power-up. Ajoute une condition qui vérifie si la variable "powerUp" du vaisseau du joueur est true. Si c'est le cas, ajoute une action qui tire des projectiles différents.

![power up](https://github.com/g404-code-gaming/SpaceShooter_CodeGaming/blob/main/instructions/images/4_powerup_2.JPG)

Les projectiles améliorés doivent être programmés de la même manière que les projectiles normaux (voir chapitre précédent). 

5. Enfin, nous allons conditionner l'apparition des power-ups.
   Ils apparaissent de la même manière que les météores : reproduire le code des météores, mais appliqué aux Power-Up. 

Voilà, tu as fini cette partie ! N'hésite pas à tester ton jeu pour voir si tout fonctionne correctement. Si tu as des erreurs, n'hésite pas à comparer ton code avec celui de la solution. Tu peux ajouter un power-up dans la scène pour le prendre immédiatement pendant tes tests et vérifier que tout fonctionne correctement.

La fin ici : [Polissage et finalisation](05_polissage_finalisation.md) 🎉
