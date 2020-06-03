## <font color=red>Objectif:</font>

Développer un modèle prédictif de la donnée « valeur foncière » pour les ventes (nature de la mutation=Vente, hors VEFA) de maison et appartement (code type local=1 ou 2) uniquement.

## <font color=red>Règles du jeu:</font>

-          utilisation du fichier 2019 uniquement

-          utilisation de composants open source uniquement (packages/librairies R ou Python)

-          langage R ou Python

-          possibilité d'utiliser d'autres données « open »


## <font color=red>Attendus:</font>

- Notebook, script ou repo git de vos travaux

-  Présentation en 30 minutes de vos résultats :

-  Stratégie d'apprentissage, choix des variables

-  Choix du modèle

-  Performance du modèle

-  Explicabilité du modèle


## <font color=red>Sources de données et documentations:</font>

 https://static.data.gouv.fr/resources/demandes-de-valeurs-foncieres/20200416-115822/valeursfoncieres-2019.txt
        
 https://static.data.gouv.fr/resources/demandes-de-valeurs-foncieres/20191220-102114/notice-descriptive-du-fichier-dvf.pdf
 
 
 ## <font color=red>Proposition de solution:</font>
 
 Dans cette partie, nous allons utiliser une stratégie d'imputation des données manquantes.

Nous allons articuler notre proposition autour de .... points:
- Charger les librairies nécessaires
- Analyse exploratoire des données
- Identifications des valeurs manquantes, outliers
- En première approximation, nous supprimerons les observations qui comportent des données manquantes
- Sans intervenir sur les outliers, nous allons construire un premier modèle qui servira de base à la suite
- La seconde étape consiste à affiner, traiter les valeurs manquantes