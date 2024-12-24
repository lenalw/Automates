1. Présentation du projet

Ce projet a pour objectif d'étudier les langages et les automates finis, ainsi que d'implémenter diverses opérations qu'on peut effectuer sur ces automates. À travers ce projet, nous explorerons la programmation orientée objet en Python pour manipuler des automates et leurs composants tels que les états et les transitions.
2. Environnement technique

Le projet est réalisé sous forme de fichier Jupyter Notebook, et utilise le langage de programmation Python. L'approche principale adoptée est la programmation orientée objet, ce qui permet de mieux gérer les objets représentant un automate, à savoir : Etat, Transition, et Automate. Ces structures de données et leurs manipulations forment le cœur de ce projet.
3. Étapes du projet

Le fichier Jupyter Notebook est divisé en plusieurs parties clés :
3.1 Présentation des classes State, Transition, et Automate

Dans cette première partie, nous introduisons les trois classes principales du projet :

    State : Représente un état d'un automate (identifiant, initial, final, et étiquette).
    Transition : Définit une transition entre deux états, liée à un symbole d'entrée.
    Automate : Modélise un automate, utilisant des états et des transitions pour simuler son comportement.

Comprendre ces classes et leurs méthodes est crucial, car elles sont au cœur de toutes les manipulations d'automates dans le projet.
3.2 Prise en main

Cette section permet de se familiariser avec la création d'automates. Vous apprendrez à créer des automates à partir d'un ensemble de transitions, ou à les charger à partir de fichiers, et à les manipuler pour effectuer différentes opérations.
3.3 Tests et complétion

Dans cette partie, des exercices de base permettent de manipuler des automates. Vous devrez compléter certaines fonctions permettant de tester des propriétés des automates, comme la complétude ou la déterminisme. Il s'agit d'écrire des fonctions qui vérifieront si un automate est déterministe, et de le compléter si nécessaire.
3.4 Déterminisation

Ici, nous nous concentrerons sur la déterminisation d'un automate. Vous serez amené à compléter une fonction permettant de créer un automate déterministe à partir d'un automate non déterministe, en gérant tous les cas possibles.
3.5 Construction d'opérations sur les automates

Cette dernière partie est plus technique. Elle implique de traduire des algorithmes mathématiques en code Python, en réalisant des opérations sur des automates. Cela inclut des opérations telles que :

    Complémentaire
    Union
    Intersection
    Concatenation

Ces opérations sont essentielles pour la manipulation des langages acceptés par les automates.
4. Conclusion

Ce projet m'a permis de développer ma capacité à résoudre des problèmes en informatique en utilisant des algorithmes bien définis et en les transposant en code Python. Ce fut également une bonne occasion de fusionner la programmation orientée objet et la programmation fonctionnelle. En manipulant les automates, j'ai appris à concevoir des algorithmes tout en améliorant mes compétences en Python.
5. Ressources

    Python : Langage utilisé pour ce projet.
    Jupyter Notebook : Utilisé pour implémenter et tester les algorithmes.
    Modules Python : Les fichiers de classes State, Transition, et Automate sont fournis pour aider à l'implémentation.
