# Notions essentielles

Dans le cadre d’une équation non-linéaire, il existe un liste assez longue méthodes (Regula falsi, méthode de la corde, méthode de la sécante, méthode de Newton) et nous illustrons dans [un premier notebook](./newton_secante.ipynb), pour un problème bien conditionné, l’évolution de l’amplitude de l’erreur, du résidu et de l’incrément afin de comprendre quel doit être le critère d’arrêt (un problème récurrent dans ce type de méthode) pour la méthode de Newton et pour la méthode de la sécante. Une interprétation graphique permet de bien comprendre d’une part la méthode et d’autre par la question de l’ordre convergence de la méthode, un point en général mal assimilé par les étudiants.

Dans [un second notebook](./explosion_thermique.ipynb), nous considérons un problème de résolution de système non-linéaire dans la veine des problèmes de que nous avons traité en lien avec les EDP semi-discrétisées en espace. Il s’agit du problème de l’explosion thermique très étudié par l’école Russe (Semenov – Frank-Kamenetskii dans les années 1920 / 1940). On cherche à trouver une solution stationnaire de l’équation de la chaleur avec terme source non-linéaire correspondant au chauffage par une réaction chimique exothermique. Lorsque le paramètre de Frank-Kamenetskii est plus petit qu’une valeur critique – notion de point limite / bifurcation – il existe une unique solution régulière à cette EDP avec condition de Dirichlet au bord (c’est-à-dire que les flux au bord arrivent à compenser la production de chaleur due aux réactions chimiques à l’intérieur). Nous étudions l'impacct du conditionnement de ce problème sur la convergence de le méthode de Newton. 