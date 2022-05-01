# Code et décode 

## Ce code est-il exact ?
### Les codes barres 

Actuellement, tous les objets fabriqués ont un code barre formé de 13 chiffres. Les douze premiers chiffres désignent le produit, le treizième est calculé à partir des 12 premiers de la façon suivante : 
pour le code $\overline{a_1a_2a_3...a_{13}}$ où $a_{13}$ est défini par la propriété : $3(a_2+a_4+a_6+a_8+a_{10}+a_{12})+a_1+a_3+a_5+a_7+a_9+a_{11}+a_{13}$ divisible par 10.<br>
Le treizième chiffre est appelé clé de controle
#### Des exemples 
1. Vérifier cette formule pour C=9 782701 158334
2. Que peut-on dire de C1= 9 782701 157334 et C2=9 782707 158334 ?
3. Considérons C3 =9 782701 153834 et interverir deux chiffres consécutifs. Ce nouveau code vérifie-t-il la formule ? 

#### Calcul de la clé de controle

1. On considère le code barre suivant 325 1241 04176x où x est la clé de contrôle. 
2. Donner des exemples de code barre ayant la même clé de contrôle. 
3. Soit $N=3(a_2+a_4+a_6+a_8+a_{10}+a_{12})+a_1+a_3+a_5+a_7+a_9+a_{11}$
  1. On note u le chiffre des unités de N
  2. Expliquer pourquoi $u+a_{13}=10$
#### Detecter les erreurs
4. Montrer que si un chiffre est erroné, l'erreur est détectée.
5. Si deux chiffres sont intervertis, l'erreur est-elle detectée ?

#### Un chiffre effacé

Peut-on trouver le chiffre manquant 325 2x37 04176 7


## Savez-vous vérifier votre numéro INSEE

Le code INSEE d'une personne est formé de 15 chiffres : 13 chiffres qui forment le numéro INSEE et un clé formée de 2 chiffres. <br>
On note N le nombre formé par les 13 premiers chiffres et r le reste de la division euclidienne de N par 97, alors la clé de controle K est le nombre 97-r. Ce qui veut dire que N+K est divisible par 97.
### Un exemple 
Calculer la clé K pour N=2 84 04 92 019 081

### Calculatrice HS devant de si grands nombres....
On peut écrire $N=A\times 10^6 + B$ avec $ 0 \leq B<10^6 $
1. Determiner A et B avec l'exemple ci-dessus.
2. Montrer que $10^6 \equiv 27[97]$ 
3. Donner le reste de A et de B par la division euclidienne par 97 (on les note $r_1$ et $r_2$)
4. Montrer que $N \equiv 27r_1+r_2[97]$ en déduire K. 

### Détecter les erreurs 
1. Modifier un chiffre de l'exemple et calculer K. Conclure
2. Echanger 2 chiffres consécutifs et calculer K. Conclure 
3. Donner un exemple d'erreur non détectable. 

## Chiffrement affine

Le principe du chiffrement affine est le suivant. On numérote de 0 à 25 et dans l'ordre alphabétique les 26 lettres de l'alphabet. <br>
On se donne deux nombres a et b, et à chaque n, rang d'une lettre L, correspond le nombre n' qui est le reste de la division euclidienne de an+b par 26. <br>
Le nombre n' est la position de la lettre L' dans l'alphabet. 
Le couple (a,b) est la clé du chiffrement affine, cette clé est secrète, elle n'est connue que de l'expéditeur et du destinataire. 
### Exemple 1
On choisit a=3 et b=5
En vous aidant du tableau :<br>

Lettre en clair | A | B |...| Z
 ---: | :---: | :--- 
n | 0 | 1| 25 
n' | 5 | 8 | ...|2
Lettre codée | F | I | ...|C

1. Coder le mot Euclide 
2. Retrouver le mot codé par XFNHH

### Exemple 2
1. Coder les mots RAGE et PEAU. 
2. Que constate-t'on ? 



