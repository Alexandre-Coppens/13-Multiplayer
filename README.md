# 13-Multiplayer

## TODO LIST
A rendre le 20 mars.

Faire un prototype Online avec un système de create, find et join session. La première map est en solo puis les joueurs se rejoignent sur une map de jeu (éventuellement avec un lobby qui sert de map intermédiaire) 5pts

Le projet doit contenir au moins une mécanique de chaque catégorie suivante. 3pts par catégorie.

[X] Spawn d'objets (en plus des joueurs) 
Exemples : Spawn ennemis, spawn de projectile, spawn de bonus à ramasser...

[ ] Des objets qui se déplacent ou rotate 
exemples : Portes qui s'ouvrent, plateformes, AI ennemi…

[X] Un système d'interaction entre le joueur et son environnement qui s'affiche sur l'UI des autres joueurs.
Exemples : Augmentation de score qui s'affiche chez tout le monde, Killfeed, inventaire de chaque joueur...

4) Un élément qui se sauvegarde entre deux lancement du jeu (En plus du nom des joueurs)
Exemples : Position, vie, niveau et expérience, équipement...

[X] Une action de personnage via un input.
Exemple : Saut, Dash, jetpack, tir, frappe…

Bien évidemment tout doit être répliqué correctement. Pas de "ça marche sur le serveur mais pas sur le client".

Vous êtes noté sur la propreté du code, les variables doivent être placées aux bons endroits, les events doivent avoir le bon setting de RPC…
Au plus vous êtes ambitieux sur le nombre ou la complexité des mécaniques, au plus je serai indulgent.

Bonus : 
- +1 si c'est fun avec un bon LD
- +1 si c'est décoré
