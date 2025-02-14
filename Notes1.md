2 types d'ombres: propre et portée: à definir
automates cellulaire pour la reconnaissance d'images quantifié

En reconnaissance d'images on mélange convolution et correlation
meme si la correlation n'est pas commutative à contrario de la convolution
Dans la formule de la correlation,c'est la même que celle de la convolution mais avec des +

# Modèle linéaire

Le filtre gaussien est à réponse impulsionnelle infini et surtout dérivable partout, paramétré par une valeur sigma qui représente son étendue spatial

# modèle fréquentiel
Modèle fréquentiel: spectre d'amplitude, spectre de phase
L'une des limites du modèle de Fourier c'est que l'image obtenu représente la valeur de frequence maximale....
transformée de fourier d'un signal carré

Notion de fantôme d'amplitude et de fantôme de phase: dans le poly

Principe de fonctionnement de l'oreille
hypothèse/principe de stationnarité

La correlation correspond à une inversion de la phase donc le produit de correlation dans le domaine spatial correspond au produit par sa conjugué dans le domaine frequentiel

## Quizz tranforméé de FOurier

1-c sinusoide
2-d signal carré
3-a penser à l'intervalle de frequence sur l'image
4-b Phénomène de recouvrement de spectre

plus grande période d'un phénomène infini périodique

1- b (on remarque un recouvrement de spectre, aliasing)
2- c exturation (linéarité de la transformée de fourier= somme des images  = somme des transformées de fourier)
3- a codage de Mitag?? (technique utilisé en imprimerie pour imprimer des teintes de niveaux de gris??); les hautes fréquences sont noyées dans les valeurs assez grandes
4- d texturation (linéarité de la transformée de fourier= somme des images  = somme des transformées de fourier)


1- b (présence de direction dominantes, orthogonales)
2- d (Pas de direction dominantes), ici on voit pas de valeurs fortes apparaissant le long des droites verticales et horizontales (images tuilab: pas de discontinuité lorsqu'on les colle; utilisé généralement comme fond d'écran)
3- a : présence d'un petit recouvrement de spectre et d'un niveau d'aliasing
4- c (image bloutée avec un opérateur de convolution: flou de Bougée? Correspond à une integrale dans le temps pendant qu'on se déplace: correspond donc à un filtre moyenneur rectangulaire dans une certaine direction) (transforée de fourier d'un signal carré: sinus cardinal)

# Transformée en ondelettes
Utile pour les conversions de formats (Jpeg 2000 etc...)
on reviendra dessus en MI206

# Le modèle statistique

# Histogramme
Principe de fonctionnement des capteurs à infrarouge: different du rayonnement du corps noir car dépend fortement de la température du plan focal

# Dérivée directionnelles

difference entre le pixel et celui de gauche (dérivée partielle par rapport à x)
difference entre le pixel et celui de dessus (dérivée partielle par rapport à y)

## Exercice : Unsharp Masking
Les modèles ensemblistes, ne pas d'y attarder... Pas abordé en cours