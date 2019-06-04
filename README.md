# 3State_Switch

Switch 3 positions (*ON/AUTO/OFF par défaut*) pour Jeedom à appliquer sur une commande de type action/Curseur.

<img src="/icon.png" alt="visuel"/>


Les valeurs retournées par le widget sont:
- *OFF* = **0**
- *ON* = **1**
- *AUTO* = **2**

Il est possible de personnaliser le libellé des cases via 3 paramètres optionnels ayant pour valeur le texte voulu et pour nom:
- **texte0**: correspond au texte pour la valeur "0" *("OFF" par défaut)*.
- **texte1**: correspond au texte pour la valeur "1" *("ON" par défaut)*.
- **texte2**: correspond au texte pour la valeur "2" *("AUTO" par défaut)*.

> Exemples:  
>**texte0**=*ABSENT* & **texte1**=*PRESENT*:  
><img src="/doc/modifTexte.gif" alt="modif1"/>  
>
>**texte0**=*ÉTEINT* & **texte1**=*ALLUMÉ*:  
><img src="/doc/modifTexte2.gif" alt="modif2"/>

En cas de valeur autre que 0 ou 1 ou 2, le widget affiche une image d'erreur:<img src="/doc/valueError.png" alt="Error"/>  
Il reste alors possible de cliquer sur la droite ou la gauche du bouton orange pour renvoyer une valeur de 0 ou 1.
