
![Logo de Concordia](https://upload.wikimedia.org/wikipedia/fr/thumb/9/97/Universit%C3%A9_Concordia_(logo).svg/1280px-Universit%C3%A9_Concordia_(logo).svg.png)

Vous faites une recherche sur la longueur des thèses et mémoires dans les universités du Québec. Vous êtes rendus à l'Université Concordia. Son [dépôt institutionnel](http://spectrum.library.concordia.ca/) vous produit un fichier CSV contenant différentes informations sur les thèses et mémoires. Ce fichier CSV est téléchargeable ici: [http://bit.ly/jhroy_devoir2_csv](http://bit.ly/jhroy_devoir2_csv).

###Rédigez un script qui puisera dans le CSV pour calculer trois nouvelles variables&nbsp;:

* Une variable appelée **_longTitre_** qui contiendra la longueur du titre de chaque thèse ou mémoire.
* Une variable appelée **_type_** qui indiquera, à partir de la colonne *thesis_degree_name*, s'il s'agit d'une maîtrise ou d'un doctorat.
* Une variable appelée **_nbPages_** qui donnera le nombre de pages total de chaque thèse ou mémoire à partir des information contenues dans la colonnes *pages_aacr*.

De toutes les variables à calculer, celle qui consiste à compter le nombre de pages est la plus difficile. C'est qu'il faut tenir compte de plusieurs possibilités.

* Dans certains cas, le nombre de pages est simple à compter. S'il est indiqué *«92 leaves : ill., photos. ; 29 cm. + 1 filmstrip (si., col.) + 24 slides (col.)»*, par exemple, cela signifie que le document compte 92 pages.
* Dans la plupart des cas, par contre, il est indiqué quelque chose comme *«xix, 131 leaves : ill. (some col.) ; 29 cm.»*, ce qui signifie que le document compte 19 pages liminaires (exprimées en chiffres romains) auxquelles il faut ajouter le nombre après la virgule, pour un total de 150 pages.

Votre script devra afficher, pour chacune des thèses ou mémoires que contient le CSV, ces trois variables dans un *print* qui dira quelque chose comme&nbsp;:

*La {thèse ou mémoire} de {nom complet de l'auteur} compte {tant} de pages. Son titre est {ceci ou cela} ({tant} de caratères).»*
*#####################################*

###Si possible&nbsp;:

Créez un nouveau fichier CSV qui ajoutera, au fichier CSV d'origine, trois nouvelles colonnes contenant les trois nouvelles variables que vous aurez calculées. Mais cela est optionnel, car nous n'avons pas eu le temps de voir comment faire dans le cours du 15 février. On va aborder cela dans le cours du 22.

Nommez ce script **devoir2.py**.

Placez-le dans un nouveau répertoire (*«repo»*) que vous baptiserez **EDM5240-devoir-2**.

Tombée : **20 février 2017, 23h59**.

Bonne chance à tous! :mortar_board:
