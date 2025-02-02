# creation de poids par rapport au criteres d'une installation
## ex: ruche
- zone spécifique a la ruche zone 2-3
- proximités fleurs
- exposition au soleil
- abris du vent
- proximité eau
- taille disponible

### Zones impossibles
peux on déjà implanter la structure: place, inconvénient
des zones en trop haute altitude ou des zones deja occupés sont impossibles a amenager pour la ruche
memes si ces zones peuvent etre les probables, elles sont retirés de la simulation

### evaluation empirique
si il n'y a pas les criteres requis comme des fleurs sur le terrain
les fleurs doivent etre placés avant, il faut donc determiner l'emplacement des fleurs en premier
l'emplacement des fleurs depends de l'emplacement des ruches et l'emplacement de la ruche depends de l'emplacement des fleurs

### Score
chaques criteres a un poid
par exemple l'abris du vent forme une carte avec un score allant de 0-1
de meme pour l'exposition au soleil
on prend l'ensemble des scores de la carte du soleil qu'on multiplie par l'importance de ce critere (poid)
que l'on ajoute a l'ensemble des scores de la carte du vent qu'on multiplie par l'importance
on obtiens alors une carte de score pour la ruche
point soleil * importance ensoleilement ruche + point vent * importance vent ruche


#### algorithme glouton
determiner une position de fleurs, puis de ruche, ensuite faire des cycles qui optimisent le positionnement jusqua la stabilité
#### equation différentielle couplée
interaction dynamique entre ruche et fleure
systeme differenctiel qui converge vers une solution optimale
#### optimisation globale
algorithme genetique pour explorer des configurations et trouver une solution optimale
