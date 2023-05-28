## Staying Alive!

Le projet est parti d'une idée de génération d'image par [Midjourney](https://www.midjourney.com/app/)

Le prompt utilisé pour la planche d'image est:

``
/imagine white background dancing skeletons in different poses having fun
``

Ensuite, comme les images étaient régulièrement disposé sur l'image, je me
suis dit: Pourquoi ne pas s'en servir comme tileset pour un CSS, et référencer
les sections en background-image sur des DIV d'une page web.

Le premier jet étant de les animer au hasard. Mais le hasard ne fait pas toujours de
bon mouvement de danse. J'ai donc hardcodé des séquences, indiquant la posture
du personnage, 4 fois par seconde. Plusieurs séquences on été codé, la posture de fin
déterminant dans la liste la suite possible (posture du début de la séquence suivante).

## TODO:

    [X] Montrer la planche des postures disponible.
    [X] Montrer la liste des postures de la séquence courante.
    [X] Montrer un marqueur sur la liste pour la posture active durant l'animation
    [X] Ajouter d'autres planches de posture (variation avec Midjourney)
    [X] Ajouter un musique techno
    [ ] Ajouter un éditeur pour ajouter de nouvelle séquence en mémoire
    [ ] Ajouter un générateur de lien pour partager des séquences de danse

