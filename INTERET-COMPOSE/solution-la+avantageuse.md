#

## Exo 4.      
- Considérons un taux d’intérêt composé  annuel de 10%. 
- Quelle est la solution la plus avantageuse :		
- a) recevoir 10.000€ ce jour ?	A choisir 
- b) recevoir 15.000€ dans 5ans ?		
- c) recevoir 20.000€ dans 15 ans ?		

- Co = 10000
- i  = 10%
- 15000 dans 5 ans
- 20000 dans 15 ans

- ? (5 & 15 ans avant)
- ? (5 & 15 ans après pour 10000)    

### Tableau des valeurs

| t                  | Aujourd’hui | 5 ans       | 15 ans      |
|--------------------|------------|------------|------------|
| **Valeur actuelle** | 10.000 €   | 9.313,82 € | 4.787,84 € |
| **Valeur acquise**  | —          | 15.000 €   | 20.000 €   |

```
Co = Ct / (1 + i) ^ t

15000 / (1 + 10%) ^ 5 = 9313.82
=VA(10%;5;0;-15000)

20000 / (1 + 10%) ^ 15 = 4787.84  
=VA(10%;15;0;-20000)

```

---

### Valeur future de 10.000 €

| Période        | t  | Montant     |
|----------------|----|------------|
| Après 5 ans    | 5  | 16.105 €   |
| Après 15 ans   | 15 | 41.772 €   |

```

Ct = Co * (1 + i) ^ t

10000 * ( 1 + 10%) ^ 5 = 16105€
VC(10%;5;0;-10000)

10000 * ( 1 + 10%) ^ 15 = 41772
VC(10%;15;0;-10000)
```