# GeneratedBand

Les tests sont utilisés sur un matériau appliqué à un widget.

## Matériau de base
![](../../images/GeneratedBand/BaseMaterial.png)

## Résultat de base
![](../../images/GeneratedBand/BaseResult.png)

## Paramètres
![](../../images/GeneratedBand/Parametres.png)

## Résultats
Les paramètres sont utilisés dans l'ordre suivant :
Width | Sharpness | Offset | DirectionSwitch | Compare
InputCoords n'est pas utilisé, il produit une image noire si 0,0, une image blanche sinon

### Paramètre Width
Width : Largeur de la bande générée.
### Resultats
Paramètres utilisés (Width 0.2)

![](../../images/GeneratedBand/1A.png)![](../../images/GeneratedBand/1B.png)

### Paramètre Sharpness
Sharpness : Dureté du bord externe de la bande, utilisable seulement avec une valeur de Width.
### Résultats
#### Avec une valeur négative
Paramètres utilisés (Width 0.2, Sharpness -10)

![](../../images/GeneratedBand/2A.png)![](../../images/GeneratedBand/2B.png)
#### Avec une valeur positive
Paramètres utilisés (Width 0.2, Sharpness 1)

![](../../images/GeneratedBand/2C.png)![](../../images/GeneratedBand/2D.png)

### Paramètre Offset
Offset : Position de départ de la bande générée, utilisable seulement avec une valeur de Width.
### Résultats
Paramètres utilisés (Width 0.2, Offset 0.5)

![](../../images/GeneratedBand/3A.png)![](../../images/GeneratedBand/3B.png)

### Paramètre Direction Switch
Direction Switch : Génère la bande à la verticale et non à l'horizontale, utilisable seulement avec une valeur de Width.
### Résultats
Paramètres utilisés (Width 0.2, DirectionSwitch true)

![](../../images/GeneratedBand/4A.png)![](../../images/GeneratedBand/4B.png)

### Paramètre Compare
Compare : Sans offset, se positionne à la valeur saisie et propage la bande générée verticalement dans les deux directions. Avec l'offset, décallage dans la direction opposée à la position saisie. Utilisable seulement avec une valeur de Width.
### Résultats
#### Compare seul
Paramètres utilisés (Width 0.2, Compare 0.5, Offset 0.0)

![](../../images/GeneratedBand/5A.png)![](../../images/GeneratedBand/5B.png)

#### Compare avec Offset
Paramètres utilisés (Width 0.2, Compare 0.5, Offset 0.2)

![](../../images/GeneratedBand/5C.png)![](../../images/GeneratedBand/5D.png)

Paramètres utilisés (Width 0.2, Compare 0.5, Offset 0.5)

![](../../images/GeneratedBand/5E.png)![](../../images/GeneratedBand/5F.png)

## Matériaux réalisables avec quelques combinaisons
Progress Bar : (Width 0.2, Compare 0.5)

![](../../images/GeneratedBand/6A.png)

![](../../images/GeneratedBand/6B.png)

Cadre 1 : 

![](../../images/GeneratedBand/6C.png)

![](../../images/GeneratedBand/6D.png)

Cadre 2 : (Width 0.2, Compare 0.5)

![](../../images/GeneratedBand/6C.png)

![](../../images/GeneratedBand/6G.png)
