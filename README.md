# 3State_Switch

Switch 3 positions (*ON/AUTO/OFF par défaut*) pour Jeedom à appliquer sur une commande de type action/Curseur.

<img src="/icon.png" alt="visuel"/>


Les valeurs retournées par le widget sont:
- *OFF* = **0**
- *ON* = **1**
- *AUTO* = **2**

Pour passer en vue switch vertical, il faut mettre le paramètre **vertical** à *1*.

Il est possible de personnaliser le libellé des cases via 3 paramètres optionnels ayant pour valeur le texte voulu et pour nom:
- **texte0**: correspond au texte pour la valeur "0" *("OFF" par défaut)*.
- **texte1**: correspond au texte pour la valeur "1" *("ON" par défaut)*.
- **texte2**: correspond au texte pour la valeur "2" *("AUTO" par défaut)*.

Il est possible de personnaliser la couleur des cases via 3 paramètres optionnels ayant pour valeur là couleur voulue et pour nom:
- **color0**: couleur de la case pour la valeur "0" *("red" par défaut)*.
- **color1**: couleur de la case pour la valeur "1" *("green" par défaut)*.
- **color2**: couleur de la case pour la valeur "2" *("#418d92" par défaut)*.


>**vertical**=*1* / **texte0**=*ÉTEINT* / **texte1**=*ALLUMÉ* / **texte2**=*STROBE* / **color0**=*tomato* / **color1**=*lime* / **color2**=*orange* :  
><img src="/doc/params.jpg" alt="parametres"/>  
>
><img src="/doc/exemple.gif" alt="exemple"/>

En cas de valeur autre que 0 ou 1 ou 2, le widget affiche une image d'erreur:

<img src="/doc/valueError.png" alt="Error"/>

Il reste alors possible de cliquer sur la droite ou la gauche du bouton orange pour renvoyer une valeur de 0 ou 1.
