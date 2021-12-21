Pourquoi les tests mettent autant de temps ?

Parce ce que le tableau que nous sommes en train de trier contiens une grande quantité de valeur, d'ou le long temps d'execution du test "isWellSortedLargeArrays".

A. S'assurer que le code de l'application ne comporte pas d'erreurs

2-Qu'avez-vous remarqué ? 

Après l'implémentation de la méthode reverseSort ligne 20, l'exécution du test ne fonctionne plus.
message d'erreur : 20:12 java: class, interface, or enum expected
Le test ne s'exécute pas car la méthode a été ajouté en dehors de la classe "SortAlgorithms".


3 et 4-Que remarquez-vous ? (après pull des autres membres du groupe de la classe "SortAlgorithms" contenant l'erreur)

Nous remarquons que les autres membres du groupe n'arrivent pas eux non plus d'executer le test

3.A.Mise en place de l'intégration continus.

6 - Que Remaquez-vous?

Nous pouvons remarquer que lorsque l'on effectue un push, on reçoit sur le github dans la section "Actions" une notification pour montrer que ca a ete executer correctement.

3.A.Mise en place de l'intégration continus.

9 - Que Remaquez-vous?

Nous pouvons remarquer que la valeur que l'on recupere est false alors que nous attendions la valeur true 

13. Allez sur votre repo Github, Que remarquez-vous ?

Nous remarquons que nos test ont failed.
