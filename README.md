GuessingGame

 jeu en Java qui consiste a laisser

L’ordinateur choisit un nombre entre 1 et 100
et toi tu dois deviner.

quand tu  proposes un nombre
Il te dit :
plus grand
ou plus petit
Tu as seulement 10 essais

 Si tu trouves tu gagnes mais
 Si tu dépasses 10 essais tu perds

Explication

Scanner : permet de lire ce que l'utilisateur tape au clavier
Random :permet de générer un nombre aléatoire

Les variables
nombreSecret : le nombre choisi par l’ordinateur
essais : nombre maximum de tentatives (10)
gagne : sert à savoir si tu as gagné ou non
La boucle

Le jeu utilise une boucle for qui tourne 10 fois maximum.
A chaque tour, le programme lit le nombre proposé par l'utilisateur.

Les conditions

À chaque essai :

si ton nombre = nombreSecret
→ tu gagnes
si ton nombre est trop petit
→ le programme dit “plus grand”
si ton nombre est trop grand
→ le programme dit “plus petit”

Fin du jeu
si tu trouves avant 10 essais
→ victoire
si tu ne trouves pas après 10 essais
→ défaite
