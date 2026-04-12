#

## Exo 1. 
- Calculer la valeur acquise d’un capital initial de 1000€, placé à 2%, au terme de 20 ans.

- Co = 1000
- t  = 20
- i  = 2%

```
Ct = 1000 * ( 1 + 2% ) ^ 20 = 1485.95

i = Ct - Co = 485.95

excel 

VC(2%;20;0;-1000) = 1485.95
```

## Exo 2 
- Calculer la valeur acquise par un capital de 1500€, placé 30 mois à 4% (intérêt composé) l’an.
- 30 mois / 12 = 2.5 ans

- Co = 1500
- t  = 2.5
- i  = 4%

```
Ct = 1500 * ( 1 + 4% ) ^ 2.5 = 1654.53

i = Ct - Co = 154.53

VC(4%;2,5;0;-1500) = 1654.53

```

## Exo 3
- Vous achetez un Bon de capitalisation de 2 500 EUR pendant 3 ans à 3,00 % brut (30% précompte) . 
- Quel sera la valeur acquise nette?								

- Co = 2500
- t  = 3 
- i  = 3%

```
VC(3%;3;0;-2500) = 2731.82

i_brut = 231.82

i_net = 162.27 = (1 - 30%) * i_brut = 0.7 * i_brut

```