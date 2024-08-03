# Classification-de-Texte-pour-les-idees-du-Grand-Paris

## Présentation et Objectifs du Projet

Le jeu de données utilisé dans ce projet provient d’échantillons collectés via une campagne de concentration nommée “Construisons la Métropole du Grand Paris”, menée par l’une des directions de la ville de Paris : la Direction de la Démocratie, des Citoyennes et des Territoires (DDCT).

Ces données sont composées de 362 lignes, représentant des propositions d’idées de projet divisées en cinq grandes thématiques :

- Transition écologique et Mobilités
- Culture et Identité
- Logement et Aménagement
- Rayonnement
- Lutte contre les inégalités

Ces idées sont proposées par des contributeurs individuels ou des collectivités. Chaque idée est décrite par 21 colonnes incluant des informations telles que la date de publication, l’objectif, la description, etc.

L'objectif de ce projet est d'appliquer une classification automatique sur le contenu des idées (colonne Description). Le but est de trouver les termes les plus pertinents et représentatifs selon chaque thématique (colonne Thématique).

## Outils et Technologies

Pour mener à bien ce projet, nous utiliserons PySpark, une bibliothèque Python pour l'analyse de données distribuée sur Apache Spark. PySpark permet aux utilisateurs de manipuler de grandes quantités de données en utilisant des outils de programmation familiers en Python. Il fournit des API pour la transformation et l'analyse de données distribuées sur un cluster de calcul, permettant une manipulation rapide et efficace des données de grande taille.

## Méthodologie

Notre classification automatique consistera à utiliser une méthode d'apprentissage non supervisé pour regrouper les données en clusters selon leur similarité. Le nombre cible de clusters est déjà connu puisque nous avons 5 thématiques (déjà étiquetées).
