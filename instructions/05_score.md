# Ajout de score et de son 🎵🔢

## Ajout de score 🔢

Comme tout bon space shooter qui se respecte, il nous faut un compteur de score ! 🚀

Pour cela, nous allons utiliser une variable globale que nous allons nommer "totalScore". Nous l'incrémenterons chaque fois que le vaisseau du joueur détruit un ennemi ou un météore. 🌠

![variable globale](images/totalScore.png)

![incrémentation du score](images/incrementationScore.png)

Nous allons ensuite afficher cette variable dans un objet texte dont le contenu initial sera "0". Nous ajouterons une action qui mettra à jour le contenu de cet objet texte avec la valeur de la variable "totalScore". 📝

![affichage du score](images/affichageScore.png)

## Ajout de son 🎵

Si tu as remarqué, notre jeu est actuellement sans son. Un jeu sans son est un peu triste. 😔 Alors, nous allons ajouter des sons pour rendre notre jeu plus vivant. 🎉

Sur les captures d'écran ci-dessus, tu as pu voir comment j'ai ajouté un son lorsqu'un ennemi est détruit. Je vais te montrer comment j'ai fait. 🎧

Ajoute une action pour jouer un son à la suite de l'action qui détruit l'objet. Tu peux choisir un son dans la bibliothèque de GDevelop ou ajouter un son que tu as téléchargé sur internet. 🌐

![son](images/son.png)

Maintenant, c'est à toi de jouer ! Ajoute des sons pour les autres événements de ton jeu. 🎶

- Quand le vaisseau du joueur est détruit
- Quand un météore est détruit
- Quand le joueur tire

## La suite ! 🚀

Ton jeu commence à être intéressant, mais il manque encore quelques fonctionnalités pour le rendre plus captivant. Il faut une fin à ce premier niveau ! 🏁
Je te propose de rajouter un boss à la fin du niveau. Ce boss sera plus gros et plus résistant que les autres ennemis. Il faudra donc lui tirer dessus de nombreuses fois pour le détruire. 🤖

allez, c'est parti ! [Boss Maman Pieuvre](07_Boss_Pieuvre.md)
