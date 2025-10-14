# Création des objets du jeu 🎮7

Maintenant que tu as GDevelop 5 prêt et configuré, il est temps de passer à la partie amusante : la création des objets de ton jeu ! Dans notre jeu Space Shooter, nous allons avoir besoin de plusieurs types d'objets : le vaisseau du joueur, les projectiles, les ennemis, les météores et les power-ups. 
On va utiliser des super assets de "Space Shooter by Pixel Boy" pour tous ces objets. Allez, c'est parti !

![assets](images/assets.png)

1. **Importation des objets** :
  
Pour importer les objets, suis ce petit cours qui va t'expliquer tout ce dont tu as besoin : --> [Objets]()

Voici les objets que tu dois positionner dans ta scène :

  - **Spaceship** : le vaisseau du joueur, qui va se déplacer et tirer des projectiles.

  - **Background** : un fond d'écran, pour rendre la scène plus vivante *(astuce, cherche Space)*

  - **Meteor** : des météores ou astéroïdes qui vont arriver vers le joueur à toute vitesse et le détruire en cas d'impact.

  - **Ennemy** : des aliens, vaisseaux ou tout autre forme de menace qui vont se diriger vers notre vaisseau pour le détruire.

  - **Projectiles** : le vaisseau du joueur va tirer des projectiles pour attaquer les différentes menances (astuce : cherche Ball ou Laser pour trouver des projectiles futuristes)

  - **Power-Up** : Un objet qui va renforcer le joueur lorsqu'il le touche. 

![positionement](images/positionement.png)

Super, tu as positionné tous les objets de ta scène. Mais il reste encore quelques réglages à faire.

2. **Création des variables de scène** : Pour ce jeu, nous allons avoir besoin de plusieurs variables de scène. Ces variables vont nous aider à gérer le comportement de nos objets. Clique en haut à droite sur ouvrir les réglages, puis dans Modifier les variables de la scène. Clique sur le bouton "Ajouter une variable" et ajoute les variables suivantes :

**randomPower** : Cette variable est un nombre. Mettons sa valeur à 0 pour le moment. Cette variable va nous permettre de conditionner plus tard les power-up du vaisseau. 🛸

![random](images/randomPower.png)

3. **Création des variables d'objets** :

**Life** : Cette variable de type Nombre est à appliquer à notre ennemi. Cette variable va nous permettre de savoir combien de points de vie il reste à l'ennemi. Règle la valeur de cette variable à 5. 💔

![life](images/life.png)

**powerUp** : Cette variable de type booléen est à appliquer à notre _Space Ship_. Cette variable va nous permettre plus tard de savoir si notre vaisseau a son power up activé ou non. 🛸

![power up](images/powerUp.png)

Et voilà, tu as de quoi commencer à jouer ! N'est-ce pas génial de voir ton jeu prendre forme ? Mais ne t'arrête pas là, il reste encore beaucoup à faire. Alors, prêt à programmer le comportement de ces objets ? Allez, c'est parti ! Direction [la prochaine partie](03_programmation_comportements.md) ! 🎉
