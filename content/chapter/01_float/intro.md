# Introduction

Le Chapitre 1 du cours introduit la représentation des nombres réels en machine et les arrondis associés, mais surtout les notions de conditionnement d’un problème et de stabilité au sens inverse. Ces notions permettent d’analyser les erreurs potentielles que l’on peut générer lorsque l’on implémente une méthode numérique sur ordinateur.

Le lecteur trouvera dans ce chapitre du JupyterBook des exemples permettant d’illustrer ce type de génération d’erreur, qu’elle mène à des pertes de chiffres significatifs ou à des erreurs plus dramatiques. 

Afin de pouvoir analyser l’influence des erreurs d’arrondi sur les résultats, il est pratique de pouvoir mener des calculs à précision fixée par l’utilisateur et on s’appuie sur le module mpmath qui est présenté dans [le premier notebook de cette section](./mpmath.ipynb). 

[Le deuxième notebook](sagemath_rump.ipynb) présente succintement le logiciel SageMath. Il permet, entre autres, de faire des calculs exacts dans le corps des fractions rationnelles de polynômes à plusieurs variables et à coefficients dans le corps des nombres rationnels. L'obtention d'une valeur exacte (non entachée d'erreur machine) est précieuse pour évaluer les potentielles erreurs effectuées en arithmétique flottante, ce qui est illustré dans le cas de l'évaluation d'une fonction. Ce logiciel libre est un outil extrêmement puissant que les élèves gagneront à connaître et pourront utiliser au besoin.
