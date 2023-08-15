
---

# Projet d'analyse EDA de Speed Dating

## Objectif du projet

Le speed dating est un processus fascinant qui permet aux individus de rencontrer de nombreuses personnes potentielles en peu de temps. Cette analyse vise à comprendre les différents facteurs qui influencent les rencontres réussies et à explorer les dynamiques et les préférences individuelles au sein de l'expérience de speed dating.
L'équipe marketing d'une application de dating a besoin d'aide pour un nouveau projet. Ils connaissent une diminution du nombre de matchs et essaient de trouver un moyen de comprendre ce qui rend les gens intéressés les uns aux autres.

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

   - **Principales découvertes:**

   Cette analyse a révélé plusieurs insights intéressants sur les facteurs qui influencent les décisions de match lors des événements de speed dating. L'attractivité semble jouer un rôle clé, tandis que l'ambition est moins valorisée. Le domaine d'études a une grande influence sur la décision de match, contrairement à l'appartenance d'un même groupe ethnique. Les participants ont tendance à mal evaluer leur attractivité et leur valeur perçue sur le marché du dating. Enfin, la communication apres un match semble jouer un rôle clé dans l'obtention d'un 2éme rendez vous en dehors de l'évenement.
   
   
   - **Recommandations:** En se basant sur les résultats de notre analyse, nous pouvons formuler les recommandations suivantes :

**Attirer un public plus large** : Notre etude a montré qu'il n'y avait aucune influence de l'age, de la difference d'age, voir de la race. Par conséquent, il serait bénéfique de s'adresser à un public plus large afin d'augmenter les chances de matchs. Il faudrait chercher à convertir un maximum de celibataires à utiliser l'application.

**Valoriser l'attractivité** : L'attractivité a été une caractéristique clé dans les décisions de match, indépendamment de l'âge et du sexe. On pourrait inclure des fonctionnalités qui mettent en valeur l'attractivité des utilisateurs, comme un bon système de photos de profil ou des filtres, voir des reglages predefinis de l'outil photo de l'application.

**Promouvoir les intérêts communs** : Les intérêts communs ont joué un rôle dans les décisions de match. On pourrait encourager les utilisateurs à partager leurs intérêts et à rechercher des personnes ayant des intérêts similaires. Ajouter une section "Interets" sur le profil qui sera visible aux autres utilisateurs et pourquoi pas l'integrer à l'algorithme de selection des profils.

**Encourager la communication après le match** : Les participants qui ont communiqué après l'événement ont eu plus de chances d'obtenir un deuxième rendez-vous. L'application pourrait encourager les utilisateurs à continuer à communiquer après un match, par exemple en fournissant des suggestions de conversation ou en offrant des récompenses pour l'engagement.

**Offrir des conseils personnalisés** : Les scores de perception déclarées des participants étaient souvent différentes de leurs valeurs perçues. L'application pourrait offrir des conseils personnalisés aux utilisateurs sur la manière d'améliorer leurs chances de match, par exemple en leur montrant comment leurs préférences se comparent à celles des autres.

**Conclusion**

nous avons pu explorer pas mal de pistes et trouver quelques insights interessants pour repondre aux problematiques de notre equipe Marketing, afin qu'ils puissent augmenter le nombre de matchs de leurs utilisateurs et ainsi les engager plus fidelement et sur le long terme.
Ces résultats fournissent des insights précieux sur les préférences et les comportements de dating des participants à ces événements de speed dating. Cependant, il est important de noter que ces résultats sont spécifiques à ce jeu de données et ne peuvent pas être généralisables à d'autres contextes ou populations.
On pourrait conduire d'autres analyses plus poussées en utilisant les variables non utilisées lors de cette etude pour decouvrir de nouveaux insights.

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
