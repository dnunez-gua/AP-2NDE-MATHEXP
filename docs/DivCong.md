# Division Euclidienne

On appelle Division Euclidienne la décomposition d'un nombre entier relatif telle que $n=bq+r$ avec $0\leq r <q$
<br> 
q est le quotient de la division euclidienne et r le reste.

###Exemple
La division de 17 par 3 : $17 =5\times 3+2$
<br>
2 est bien compris entre 0 et 3.

## Exercices

### Exercice 1

- Effectuer les divisions euclidiennes de : 
  * 45 par 2
  * 497 par 23
  * 47 par 3
  * 750 par 27
- Ecrire la division euclidienne de 121 par 23. 
En déduire la division euclidienne de -121 par 23

### Exercice 2 Vrai / faux

Vérifier que $287=18\times 15 +17$

- Dans la division de 287 par 15, le quotient est égal à 18
- Dans la division de 287 par 18, le quotient est égal à 15
- Dans la division de -287 par 18, le quotient est égal à -15 et le reste vaut -17
- Dans la division de -287 par 18, le quotient est égal à -16 et le reste vaut 1
- Si 15 est le reste de la division euclidienne de a par b alors -15 est celui de la division euclidienne de -a par b.

### Exercice 3 
Trouver un nombre qui, divisé par 13, donne pour reste 9 et, divisé par 15 donne le même quotient et le reste 1. 

### Exercice 4
Dans la division euclidienne de a par 11, le reste est égal à 8. Dans la division de b par 11 le reste est égal à 3. <br>

- Donner le reste de la division de $a+b$ par 11
- Donner le reste de la division de $a^2$ par 11


### Exercice 5 
Quel jour étions nous le 14 juillet 1789 ?

# Congruences

* Soit $a$ et $b$ deux nombres entiers relatifs et $n$ un nombre entier naturel non nul. $a$ et $b$ ont le même reste par la division euclidienne par $n$ si et seulement si $a-b$ est un multiple de $n$.

* Soit $a$ et $b$ deux nombres entiers relatifs et $n$ un nombre entier naturel non nul. Dire que $a$ et $b$ sont congrus modulo n signifie que $a$ et $b$ ont le même reste par la division euclidienne par $n$. On note $a\equiv b[n]$

### Exemple 

* $21 = 4 \times 5 +1$ et $25 =4\times 6 +1$ donc $21\equiv 25[4]$
* $-19\equiv -5[7]$

## Conséquences
 
* si r est le reste de la division euclidienne de $a$ par $n$ alors $a\equiv r [n]$
* $a\equiv a[n]$ ; si $a\equiv b[n]$ alors $b\equiv a[n]$ ; si $a\equiv b[n]$ et $b\equiv c[n]$ alors $a\equiv c[n]$
* propriétés :
     * si $a\equiv b[n]$ et $c\equiv d[n]$ alors $a+c\equiv b+d[n]$ ; $a-c\equiv b-d[n]$ et $ac\equiv bd[n]$
     * si $a\equiv b[n]$ alors pour tout entier $p$ : $a^p\equiv b^p[n]$
     * si $a\equiv b[n]$ alors $a+c\equiv b+c[n]$ et $ac\equiv bc[n]$

<b>Attention</b> : on ne peut pas simplifier les congruences : $16\equiv 20[4]$ n'implique pas que $8\equiv 10[4]$

## Exercices
### Exercice 1 : vrai/ faux
- Tout entier relatif est congru modulo 5 à 1,2,3 ou 4.
- $257\equiv 10[9]$ et $244 \equiv 205[13]$
- On a $751=17\times 43 +20$ alors $751\equiv 20[17]$ et $751\equiv 20[43]$
- Si $a\equiv 3[7]$ et $b\equiv 5[7]$ alors $3a+8b\equiv 0[7]$
- Si $2a\equiv 2b[n]$ alors $a\equiv b[n]$
- Si $a\equiv b[6]$ alors $a\equiv b[3]$
- Si $2a\equiv 2b[2n]$ alors $a\equiv b[n]$

### Exercice 2
Table d'addition et de multiplication <br>
Dresser la table d'addition et la table de multiplication [4]


### Exercice 3
On suppose que $a\equiv 3[5]$ et $b\equiv[5]$.<br>
Calculer $7a^2+4b^2$ modulo 5. Quel est le reste de la division euclidienne de $7a^2+4b^2$ par 5
 
### Exercice 4
Résoudre les équations suivantes <br>

- $7x\equiv 3[11]$
- $5x\equiv 3[10]$
- $5x\equiv 0[10]$
- $7x\equiv 3[10]$
- $5x+25\equiv 56[7]$
- $8x-23\equiv 5x-45[17]$
