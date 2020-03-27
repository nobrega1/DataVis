### 1) Comment et pourquoi le code est-il divisé en plusieurs fichiers?
Dans mon cas, j'utilise l'outil webpack et des modules comme Babel pour me permettre de séparer mon code en plusieurs petit boût. Webpack me permet de "packer" tous les morceaux de code que j'ai envie en les important dans un fichier principal. Cette façon de faire permet au code de gagner en lisibilité et surtout devient plus facile à mettre à jour. Dans un cas où tout le code serait dans un seul fichier, le changement d'une seule variable pourrait corrompre tout le travail. 

### 2) Comment le nom du pays est-il affiché quand la souris passe sur une bulle?
Le nom du pays est encapsulé dans une élément <text> et ajouté au SVG lorsque la souris passe sur une bulle (mousover). La librairie D3 calcule la positon du nom en fonction de la taille de la bulle. 