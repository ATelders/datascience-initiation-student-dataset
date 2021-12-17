# datascience-initiation-student-dataset
Ce repository regroupe une série de notebooks destinés aux Data Scientists Juniors (niveau 3ème) qui rejoignent l'équipe Data Science pour quelques jours.

Ils leur permettent de se plonger dans l'univers de la Data Science à travers un cas d'étude simple, inspiré du dataset (adapté) de l'University of California : [ici](https://archive.ics.uci.edu/ml/datasets/student+performance).

Description des notebooks :

* [student-notebook-1-explore](./student-notebook-1-explore.ipynb) permet d'importer et d'explorer le jeu de données et de repérer certaines incohérences volontairement introduites dans les valeurs.
* [student-notebook-2-correct](./student-notebook-2-correct.ipynb) explique comment  corriger les valeurs incohérentes. Ce notebook est complété par [student-notebook-2-pandas-data-selection](./student-notebook-2-pandas-data-selection.ipynb) qui explique, avec un DataFrame simple, les sélections de données via Pandas.
* [student-notebook-3-transform](./student-notebook-3-transform.ipynb) explique pourquoi il est nécessaire de transformer certaines informations enregistrées sous formes de chaines de caractères (ex. "yes" / "no") en vecteurs de 0 et 1.
* [student-notebook-4-train](./training-student/student-notebook-4-train.ipynb) détaille la création des jeux de données X_train, X_test, y_train et y_test ainsi que l'entrainement et l'évaluation du modèle.

Description des jeux de données :

* [student-0-original](./student-0-original.csv) : jeu de données original tel que fourni par l'UCI
* [student-1-start](./student-1-start.csv) : jeu de données adapté (suppression de certaines colonnes et corruption de la colonne "age")

Le répertoire [completed_notebooks](./completed_notebooks) contient le jumeau de chaque notebook avec le code complété ainsi que les jeux de données intermédiaires.
