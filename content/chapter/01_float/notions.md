# Illustration du cours

Le premier notebook de cette section permet de comprendre avec quelle précision on doit travailler pour obtenir un résultat précis sur la fonction de Rump et d’analyser les difficultés que l’on rencontre (un exemple proposé en PC permettra d’identifier qu’il s’agit en fait d’un problème mathématique très mal conditionné). 

Le fait de travailler avec une représentation finie des nombres en machine conduit à la perte de certaines propriétés mathématiques et à des « règles » d’implémentation de certaines suites d’opération comme on le voit dans le deuxième notebook dédié à la perte de l’associativité de l’addition.

Un domaine classique de l’analyse numérique est celui de la résolution de systèmes linéaires qui fera l’objet du chapitre 4 et pour lequel on définira la notion de conditionnement d’une matrice. En attendant, un troisième notebook permet de comprendre l’influence de la structure de la matrice sur le conditionnement du problème et d’en avoir une illustration graphique. Cette interprétation permet de bien montrer que le conditionnement est une propriété intrinsèque du problème que l’on cherche à résoudre et n’a rien à voir avec une quelconque méthode numérique de résolution. 

Dans le quatrième notebook, nous reprenons l’illustration de l’influence du conditionnement sur l’évaluation d’une fonction scalaire au moyen de diverses méthodes de calcul. Le lecteur constatera que le choix de l’algorithme d’évaluation a un impact sur la qualité du résultat quand on travaille avec un problème mal conditionné. 

Enfin, dans un cinquième notebook, nous considérons un problème bien conditionné et montrons que l’utilisation d’un algorithme instable au sens backward peut mener à une perte de précision, éventuellement catastrophique.
