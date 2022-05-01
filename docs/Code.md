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
  2. Expliquer pourquoi u+a_{13}=10
#### Detecter les erreurs
4. Montrer que si un chiffre est erroné, l'erreur est détectée.
5. Si deux chiffres sont intervertis, l'erreur est-elle detectée ?

#### Un chiffre effacé

Peut-on trouver le chiffre manquant 325 2x37 04176 7
