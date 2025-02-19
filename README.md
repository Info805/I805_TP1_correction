# TP1 Compilation : Evaluateur d'expressions arithmétiques infixées
On utilise JFlex pour l'analyseur lexical et CUP pour l'analyseur syntaxique.

**Sous Dossier [Exercice1](Exercice1) :**  
Correction de l'exercice 1, évaluateur d'expressions arithmétiques infixées sur les nombres entiers.

Différentes versions pour l'exercice 1 :  
- v1 : 4 opérateurs uniquement (+, -, *, /) - pas de gestion des erreurs : 
[branche Exercice1_v1](../Exercice1_v1/Exercice1)
- v2 : ajout des opérateurs pour le modulo et le moins unaire - gestion des erreurs (division par zéro) : 
[branche Exercice1_v2](../Exercice1_v2/Exercice1)
- v3 : ajout de la gestion des numéros de ligne et de colonne : 
[branche Exercice1_v3](../Exercice1_v3/Exercice1)
    
**Sous Dossier [Exercice2](Exercice2) :**  
Correction de l'exercice 2, ajout de l'utilisation de variables et gestion des commentaires.

Différentes versions  pour l'exercice 2 :  
- v1 : 4 opérateurs uniquement (+, -, *, /) - pas de gestion des erreurs : 
[branche Exercice2_v1](../Exercice2_v1/Exercice2)
- v2 : ajout des opérateurs pour le modulo et le moins unaire - gestion des erreurs (variable indéfinie/division par zéro): 
[branche Exercice2_v2](../Exercice2_v2/Exercice2)
- v3 : ajout de la gestion des numéros de ligne et de colonne : 
[branche Exercice2_v3](../Exercice2_v3/Exercice2)

Normalement l'exécution de la tâche build (via gradle) devrait générer un jar pour chaque exercice 
(Exercice1/build/lib/Exercice1.jar et Exercice2/build/lib/Exercice2.jar).  
On peut les utiliser pour lancer l'analyseur : 

```
java -jar Exercice2/build/libs/Exercice2.jar tpEvaluateurSource.txt
```

Ce qui donne alors le résultat suivant :  

Fichier source :  
![Copie écran fichier source](exempleSource.jpg)  

Résultat :  
![Copie écran résultat exécution](exempleEvaluation.jpg)  
