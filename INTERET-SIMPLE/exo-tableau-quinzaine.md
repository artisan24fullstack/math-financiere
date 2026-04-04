# 

## Exos 

- Un épargnant place, à partir du 5 janvier 2020, 1500€ tous les 5 du mois jusqu’au 5 décembre 2020. 						
- Le taux  est de 3,96%, les intérêts étant calculés par quinzaine entière. 						
- De plus, une prime de fidélité de 0.95% annuelle lui sera octroyée pour les versements qui sont restés 10 mois consécutifs sur le compte. 						
- Combien l’épargnant récupèrera-t-il le 31 décembre 2020 ?						

- i = 3.96%
- prime de fidélité = 0.95%
- t en quinzaine  

```
I = Co * i * t/24

colonne 1 date 05 de chaque mois / 2020
colonne 2 durée 23 ( 24 - 1) et pour le reste -2 à chaque fois (par quinzaine) 
colonne 3 montant 1500

ligne 1 
D86 intéret = montant * $i$ * (23/24) 
E86 prime   = montant * $prime$
F86 total   = montant + intérêt + prime

```
| A85    | B85    | C85     | D85   | E85    | F85      |

| date    | durée | montant | int   | prime  | TOTAL    |
|---------|-------|---------|-------|--------|----------|
| 05-01-20| 23    | 1500    | 56,93 | 14,25  | 1.571,18 |
| 05-02-20| 21    | 1500    | 51,98 | 14,25  | 1.566,23 |
| 05-03-20| 19    | 1500    | 47,03 |        | 1.547,03 |
| 05-04-20| 17    | 1500    | 42,08 |        | 1.542,08 |
| 05-05-20| 15    | 1500    | 37,13 |        | 1.537,13 |
| 05-06-20| 13    | 1500    | 32,18 |        | 1.532,18 |
| 05-07-20| 11    | 1500    | 27,23 |        | 1.527,23 |
| 05-08-20| 9     | 1500    | 22,28 |        | 1.522,28 |
| 05-09-20| 7     | 1500    | 17,33 |        | 1.517,33 |
| 05-10-20| 5     | 1500    | 12,38 |        | 1.512,38 |
| 05-11-20| 3     | 1500    | 7,43  |        | 1.507,43 |
| 05-12-20| 1     | 1500    | 2,48  |        | 1.502,48 |
|         |       |         |       |        | somme = 18 384.9 |
