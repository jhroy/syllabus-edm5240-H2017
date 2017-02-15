
![Logo de Concordia](https://upload.wikimedia.org/wikipedia/fr/thumb/9/97/Universit%C3%A9_Concordia_(logo).svg/1280px-Universit%C3%A9_Concordia_(logo).svg.png)

Vous faites une recherche sur la longueur des thèses et mémoires dans les universités du Québec. Vous êtes rendus à l'Université Concordia. Son [dépôt institutionnel](http://spectrum.library.concordia.ca/) vous produit un fichier CSV contenant différentes informations sur les thèses et mémoires. Ce fichier CSV est téléchargeable ici: [http://bit.ly/jhroy_devoir2_csv](http://bit.ly/jhroy_devoir2_csv).

###Rédigez un script qui créera un nouveau fichier CSV à partir du premier.

Le nouveau fichier contiendra **trois nouvelles colonnes** :

* Une colonne appelée **_longTitre_** qui contiendra la longueur du titre de chaque thèse ou mémoire
* Une colonne appelée **_type_** qui indiquera, à partir de la colonne *thesis_degree_name*, s'il s'agit d'une maîtrise ou d'un doctorat
* Une colonne appelée **_nbPages_** qui donnera le nombre de pages total de chaque thèse ou mémoire à partir des information contenues dans la colonnes *pages_aacr*.

De toutes les colonnes à ajouter, celle qui consiste à compter le nombre de pages est la plus difficile. C'est qu'il faut tenir compte de plusieurs possibilités.

* Dans certains cas, le nombre de pages est simple à compter. S'il est indiqué *«92 leaves : ill., photos. ; 29 cm. + 1 filmstrip (si., col.) + 24 slides (col.)»*, par exemple, cela signifie que le document compte 92 pages.
* Dans la plupart des cas, par contre, il est indiqué quelque chose comme *«xix, 131 leaves : ill. (some col.) ; 29 cm.»*, ce qui signifie que le document compte 19 pages liminaires (exprimées en chiffres romains) auxquelles il faut ajouter le nombre après la virgule, pour un total de 150 pages.

Nommez ce script **devoir2.py**.

Placez-le dans un nouveau répertoire (*«repo»*) que vous baptiserez **EDM5240-devoir-2**.

Tombée : **20 février 2017, 23h59**.

Bonne chance à tous! :mortar_board:
