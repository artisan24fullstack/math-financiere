#


### Exos
- Comparer le capital obtenu après 1 an :					
- a) 100000 € au taux annuel de 8%					
- b) 100000 € au taux semestriel de 4%
- c) quel est taux annuel effectif équivalent du taux périodique utilisé au point (b) ?					

```
a)
100000 * (1 + 8%) ^1 = 108000
=VC(8%;1;0;-100000)

b)
100000 * (1 + 4%) ^2 = 108160
=VC(4%;2;0;-100000)

c)
(1 + 4%) ^2 -1 = 0.0816 = 8.16%
=TAUX.EFFECTIF(8%;2)

```

####
- Calculer la valeur acquise par un capital de 100000€ 
- placé pendant 18 mois à un taux nominal annuel capitalisable 
- par trimestre de 8 % ?							

- Co = 100000
- t = 6 trimestres = 18 mois 
- i  = 8%
- m  = trimestres

- i_trim = 2% = 8% / 4  

```
Ct = 100000 * (1 + 2%) ^ 6 = 112616.241926

I  = 12616.24

=VC(2%;6;0;-100000)
```