# Notions essentielles

[Le premier notebook](./error.ipynb) de cette section montre comment le fait de travailler avec une représentation finie des nombres en machine conduit à la perte de certaines propriétés mathématiques et à des « règles » d’implémentation de certaines suites d’opération comme on le voit dans le deuxième notebook dédié à la perte de l’associativité de l’addition.

Un domaine classique de l’analyse numérique est celui de la résolution de systèmes linéaires qui fera l’objet du chapitre 4 et pour lequel on définira la notion de conditionnement d’une matrice. En attendant, [un deuxième notebook](conditioning.ipynb) permet de comprendre l’influence de la structure de la matrice sur le conditionnement du problème et d’en avoir une illustration graphique. Cette interprétation permet de bien montrer que le conditionnement est une propriété intrinsèque du problème que l’on cherche à résoudre et n’a rien à voir avec une quelconque méthode numérique de résolution. 

Dans [le troisième notebook](stability.ipynb), il est question de la stabilité d'un algorithme dans le cas :
- de l'évaluation d’une fonction scalaire mal conditionné : le lecteur constatera que le choix de l’algorithme d’évaluation a un impact sur la qualité du résultat quand on travaille avec un problème mal conditionné;
- de l'évaluation d’une fonction scalaire bien conditionné : dans ce cas l’utilisation d’un algorithme instable au sens backward peut mener à une perte de précision, éventuellement catastrophique.
