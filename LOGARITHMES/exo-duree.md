#

## Exos 1.

- Combien d’années sont nécessaires pour qu’un capital de 100.000€, placé à 2 %, double ?

- Co = 100000
- i  = 2%
- Ct = 200000
  
```
t = LOG( 200000 / 100000) / LOG ( 1 + 2%) = 35 ans

NPM(2%;0;-100000;200000) = 35 ans
```


## Exos 2.
- Si le taux annuel est de 3,5 %, après combien de temps un capital de 1500 € devient-il 1876 € ?
  
- Co = 1500
- i  = 3.5%
- Ct = 1876
  
```
t = LOG( 1876 / 1500) / LOG ( 1 + 3.5%) = 6.5 ans

NPM(3,5%;0;-1500;1876) = 6.5 ans
```

## Exos 3.
- Combien y a-t-il d’années (+mois et jours) 
- faut il pour qu’un capital de 100 000€ 
- atteigne la valeur acquise brute de 150.000€, 
- compte tenu d’un taux de 6% ?"								

- Co = 100000
- Ct = 150000
- i  = 6%
  
```
NPM(6%;0;-100000;150000) = 6,958515633

6 ans + 11 mois + 16 jours

+ 0,958515633 * 12 = 11,5021876 = 11 mois
+ 0,5021876   * 30 = 15,065628  = 16 jours  
```