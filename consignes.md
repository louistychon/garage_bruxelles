# Bienvenu au garage de  la  ville de Bruxelles.
>Dans cet exercice, nous aurons des clients qui iront se faire réparer leur véhicule chez le garagiste. Le garagiste fera un devis et leur une facture. Par la suite, les clients iront à la caisse afin d'acheter les pièces puis le garagiste réparera le véhicule.


## Description des clients
> Les clients ont un nom, un véhicule, de l'argent, un problème, ils savent aller à un endroit, prendre une facture et payer. Les clients sont dans une salle d'attente.

|nom|vehicule|argent|probleme|facture|goTo|pay|
|---|---|---|---|---|---|---|
|Marcus|BMW|200|rouleur|
|Julien|Peugeot|100|pneu crevé|
|Léa|Renault|300|feu avant cassé|
|Serge|Mercedes|500|moteur en panne|
|Léo|Audi|600|huile à moetur vide|

## Description du garagiste
> le garagiste lui reçoit les clients dans son bureau. Tout d'abord, il fait les devis avant de leur faire une facture.
> Attention le garagiste fait à chaque fois sortir le client avant de prendre le suivant.
> dans son cabinet il y a un chien de race berger allemand pour garder les lieux contre les voleurs. Son chien aboie à tous mes deux secondes dans la console (bonus). Le devis coûte 45€. Les clients ont eu un devis dans de sortirs du bureau.

|nom|argent|devis|facture|clientIn|ClientOut|
|---|---|---|---|---|---|
|Debugger|0|[chien]


### Grille des devis

|probleme|pieces|
|---|---|---|---|---|---|

|rouleur|`rouleur neuf`|
|pneu crevé|`pneu neuf`|
|feu avant cassé|`feu  neuf`|
|moteur en panne|`moteur neuf`|
|huile à moetur vide|`huile`|


## Description de la caisse
> la caisse est un endroit où les clients payent. Les clients iront payer la facture.
> s'ils ont assez d'argent le garagiste pourra acheter les pièces et effectuer la réparation.
> dans le cas où le client n'a pas assez d'argent le garagiste ne pourra pas acheter les pièces dont la voiture ira à la casse.

## Prix des pièces
|piece|prix|
|---|---|
|rouleur|`45€`|
|pneu crevé|`50€`|
|feu avant cassé|`60€`|
|moteur en panne|`800€`|
|huile à moetur vide|`100€`|


# Vérification

> Grâce à votre débuggeur suivez à la trace l'évolution de chacun de vos clients. Vérifier bien qu'il quitte à chaque fois la salle d'attente avant d'entrer dans le bureau et qu'ils sortent bien du bureau avant de laisser quelqu'un d'autre entré.