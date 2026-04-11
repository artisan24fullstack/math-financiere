#

## Exos 3.      
- Comparer la valeur acquise par un capital de 1000€, placé à 1,25% l’an, en intérêts simples, 
- puis composés, au terme de 1 ans, 5 ans (intérêts composés)

| Paramètre        |   1 an      |  5ans       |
|------------------|-------------|-------------|
| C0               | 1000        | 1000        |
| t                | 1           | 5           |
| i                | 1,25%       | 1,25%       |
|                  |             |             |
| **Simple**       |             |             |
|                  | 1.012,50 €  | 1.062,50 €  |
|                  |             |             |
| **Composé**      |             |             |
|                  | 1.012,50 €  | 1.064,08 €  |


```
Int simple 

[cas 1] 1000 * ( 1 + 1.25% * 1) = 1.012,5€

[cas 2] 1000 * ( 1 + 1.25% * 5) = 1062.5€

Int composés

[cas 1] 1000 * ( 1 + 1.25% ) ^ 1 = 1012.5 

[cas 2] 1000 * ( 1 + 1.25% ) ^ 5 = 1064.08
```
```
EXCEL Int composés

[cas 1] VC(1,25%;1;0;-1000) = 1012.5 

[cas 2] VC(1,25%;5;0;-1000) = 1064.08
```
