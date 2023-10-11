# Premier principe

## La base

Le premier principe de la thermodynamique établit que, lors de toute transformation, il y a une **conservation de l'énergie** [(Wikipedia)][1]


Vous connaissez certainement la célèbre phrase :

```admonish quote
Rien ne se perd, rien ne se crée, tout se transforme
```

En effet, il n'est pas possible de "créer" de l'énergie, mais seulement de la transformer (électrique -> mécanique, solaire -> électrique, ...).
C'est la même chose en chimie, un **système** (portion de l'environnement, qui peut être fermée (ex: moteur de voiture) ou ouverte (ex: turbine d'avion) ne peut ni créer de l'énergie
ni en faire disparaitre. 

D'ailleurs, **l'énergie d'un système** (U) est relativement simple a exprimer.

$$ U = U_{int} + U_c $$

L'énergie d'un système correspond a la somme de son énergie interne (énergie de liaison des molécules, etc...) ainsi que de son énergie cinétique (la vitesse des particules, c'est a dire sa température)


Mais l'énergie interne $U_{int}$ est excessivement difficile (voire impossible) a déterminer, mais il y a un avantage, c'est qu'elle est **constante**, et que de manière générale
on ne sera jamais intéréssé par l'énergie d'un système, mais plutôt par la différence d'énergie entre un moment A et un moment B.

$$ \Delta U = U_B - U_A = (U_{int} + U_{cB}) - (U_{int} + U_{cA}) = \Delta U_c $$ 

Le terme de l'énergie interne disparaît ! Et il ne reste que $U_c$.

Mais que vaut $U_c$ ? Et bien il y a deux moyens d'ajouter de l'énergie a un système, soit via de la **chaleur** (Q) (on réchauffe le système) soit via un **travail** (W) mécanique. 

Il est donc possible d'exprimer

$$U_c = Q + W$$

(Un $Q$ ou un $W$ **positif** signifient que le système **recoit** de l'énergie)

ainsi que

$$\Delta U = \Delta Q + \Delta W$$

Il faut donc bien comprendre qu'a chaque transformation d'un système, l'énergie ne peut varier qu'en fonction de **chaleur** (on réchauffe/refroidit) ou bien de **travail**.


Et voila ! Nous sommes arrivés à la première loi de la thermodynamique. 



Il reste une loi importante a connaitre, la première loi de Joules:

```admonish abstract title="Definition"
Le $\Delta U$ d'un gaz parfait ne dépend QUE de la température de ce gaz. 

$\Delta U = C_v \Delta T$

$\Delta U = C_p \Delta T$

$C_v$ et $C_p$ étant les capacités calorifiques du gaz respectivement a volume constant/pression constante.


Donc, si un travail provoque une variation de l'énergie (U) du système, alors sa température aura changé également.
```

Il est possible de visualiser cette loi par le fait que si l'on comprime un gaz, sa paroi sera en mouvement (le temps de la compression), 
et accélèrera le mouvement des particules qui la touchent (cf: une batte de baseball en mouvement accélère la balle qui rebondit dessus).
Et comme la température correspond (en gros) a la vitesse des particules, un travail donné au système augmentera la température de celui ci.

## Les transformations

Nous parlions de transformations, mais il est également important de bien comprendre les différents types de transformations possibles:

### Transformation isotherme

Une transformation **isotherme** est une transformation durant laquelle la température du système est **constante**.

```admonish warning

Cela ne veut PAS dire qu'il n'y a pas d'échange de chaleur avec l'extérieur. Cela signifie juste qu'entre le début et la fin de la transformation la température
nette du système ne change pas.

```

Étant donné que $\Delta U = Q + W = C_{v} \Delta T$ (ou $C_p$ en fonction), si la température est constante, $\Delta T = 0$, nous pouvons donc concure que :

$$ \Delta U = 0 \Longleftrightarrow Q = -W $$

En effet, l'énergie gagnée par le système en travail devra être "éliminée" par une perte de chaleur du système.


### Transformation isobare
### Transformation isochore
### Transformation adiabatique




[1]: <https://fr.wikipedia.org/wiki/Premier_principe_de_la_thermodynamique>
