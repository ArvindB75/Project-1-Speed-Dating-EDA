
---

# Projet d'analyse EDA de Speed Dating

## Objectif du projet

L'objectif principal de ce projet est d'analyser le jeu de données du speed dating pour comprendre les facteurs qui influencent l'attraction entre deux personnes. Nous cherchons à répondre à des questions telles que : Qu'est-ce qui rend une personne attirante pour une autre lors d'un speed dating ? Quel rôle jouent des facteurs tels que l'âge, la race, les intérêts, etc. ?

## Méthodologie

Pour analyser les données, nous utiliserons diverses techniques statistiques. Cela peut inclure l'analyse descriptive, l'analyse de corrélation, etc. Nous utiliserons également des techniques de visualisation pour illustrer nos résultats.
Le jeu de données a quelques valeurs manquantes. Par exemple, la colonne 'positin1' a 1846 valeurs manquantes, 'undergra' a 3464 valeurs manquantes, 'mn_sat' a 5245 valeurs manquantes, et 'tuition' a 4795 valeurs manquantes. Il est probable que ce jeu de données nécessite un certain prétraitement pour gérer ces valeurs manquantes avant de pouvoir être utilisé pour l'analyse de données ou l'apprentissage automatique. La gestion de ces valeurs manquantes peut inclure des stratégies telles que l'imputation, la suppression des valeurs manquantes, ou l'utilisation d'algorithmes qui peuvent gérer les valeurs manquantes.

## Instructions d'installation

Le projet est réalisé en utilisant Python et nécessite l'installation des packages suivants :

- pandas
- numpy
- matplotlib
- seaborn

Ces packages peuvent être installés à l'aide de pip :

```
pip install pandas numpy matplotlib seaborn
```

## Comment utiliser le jeu de données

Le jeu de données est un fichier CSV nommé 'DS_speed_dating.csv'. Il peut être chargé en Python en utilisant la bibliothèque pandas :

```python
import pandas as pd

data = pd.read_csv('chemin_vers_le_fichier/DS_speed_dating.csv', encoding='ISO-8859-1')
```

## Résultats et conclusions

**1. Statistique Descriptives**

Le jeu de données comprend 8 378 observations et 195 variables. Les participants sont à peu près également répartis entre les hommes (49,1 %) et les femmes (50,9 %). Les âges des participants varient de 18 à 58 ans, avec une moyenne d'environ 26 ans. Les participants proviennent de divers domaines d'études, notamment le droit, les mathématiques, les sciences sociales, la médecine, l'ingénierie, l'éducation, les arts et d'autres.

**2. Analyse Univariée**

J'ai examiné la distribution des évaluations pour chaque attribut. J'ai constaté que l'attractivité est l'attribut qui reçoit généralement les évaluations les plus élevées, tandis que l'ambition reçoit les évaluations les plus basses. Cela suggère que l'attractivité est un attribut très apprécié lors des événements de speed dating, tandis que l'ambition est moins valorisée.

**3. Analyse Bivariée**

J'ai analysé la corrélation entre chaque attribut et la décision de match. J'ai constaté que l'attractivité a la plus grande corrélation positive avec la décision de match, ce qui suggère qu'elle joue un rôle important dans la décision de choisir un partenaire potentiel. J'ai également constaté que les intérêts communs ont une plus grande influence sur la décision de match que l'appartenance au même groupe ethnique.

**4. Analyse Multivariée**

J'ai examiné comment plusieurs variables interagissent entre elles et influencent la décision de match. J'ai constaté que les participants ont tendance à surestimer leur attractivité et leur valeur sur le marché du dating. De plus, J'ai constaté que le taux de match est légèrement plus élevé pour les participants qui étaient les premiers rendez-vous dans une session de speed dating, comparativement à ceux qui étaient les derniers.

**6. Conclusion**

Cette analyse a révélé plusieurs insights intéressants sur les facteurs qui influencent les décisions de match lors des événements de speed dating. L'attractivité semble jouer un rôle clé, tandis que l'ambition est moins valorisée. Les intérêts communs ont une plus grande influence sur la décision de match que l'appartenance au même groupe ethnique. Les participants ont tendance à surestimer leur attractivité et leur valeur sur le marché du dating. Enfin, les premières impressions semblent jouer un rôle important, avec un taux de match légèrement plus élevé pour les premiers rendez-vous dans une session de speed dating.

Ces résultats fournissent des insights précieux sur les préférences et les comportements de dating des participants à ces événements de speed dating. Cependant, il est important de noter que ces résultats sont spécifiques à ce jeu de données et peuvent ne pas être généralisables à d'autres contextes ou populations.

## Licence et citation

Ces données de speed dating ont été recueillies auprès de participants à des événements de speed dating expérimentaux. Les événements ont été organisés par les professeurs de la Columbia Business School, Ray Fisman et Sheena Iyengar, pour leur article "Gender Differences in Mate Selection: Evidence From a Speed Dating Experiment". Le jeu de données est publiquement disponible pour être utilisé dans la recherche et l'enseignement.
Ce jeu de données est librement disponible pour une utilisation non commerciale sur Kaggle.com.
Ce jeu de données peut être utilisé à diverses fins dans les domaines des sciences sociales, de la psychologie et de l'apprentissage automatique. Par exemple, il peut être utilisé pour étudier les facteurs qui influencent l'attraction et la prise de décision dans les rencontres, pour examiner les préférences raciales dans les rencontres, ou pour construire des modèles prédictifs pour l'appariement des partenaires. La grande variété de variables dans le jeu de données permet d'explorer de nombreuses questions de recherche et hypothèses possibles.

## Contributions

Les contributions à ce projet sont les bienvenues. Si vous souhaitez contribuer, veuillez d'abord ouvrir une issue pour discuter de ce que vous souhaitez changer.

## Contact

Si vous avez des questions ou des commentaires sur ce projet, veuillez me contacter à :

*abajolah@gmail.com*

---
