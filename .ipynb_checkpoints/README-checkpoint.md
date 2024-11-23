# Projet-vaccination
Analyse exploratoire de données, Eugénie Porre et Solène Losantos

<!-- #region -->
Ce dataset contient un ensemble de données relatives à la vaccination de différentes pathologies au sein des départements français.
Voici une analyse des colonnes présentes dans ce dataset:

# ANALYSE DES COLONNES:

date : La date à laquelle les données ont été collectées ou mises à jour. Cela pourrait être important pour analyser les tendances dans le temps.

regroupement_pathologie : Un regroupement des pathologies => classer les pathologies en catégories plus larges (maladies respiratoires, cardiovasculaires, etc.).

pathologie : Le nom spécifique de la pathologie pour laquelle les données sont collectées (par exemple, diabète, hypertension, etc.).

region_residence : La région où les personnes sont domiciliées. Cela peut être utilisé pour des analyses géographiques.

libelle_region : Le nom de la région (ex : Île-de-France, Provence-Alpes-Côte d'Azur). 

departement_residence : Le département de résidence des personnes concernées. Cela permet d’affiner l’analyse géographique à un niveau administratif plus précis.

libelle_departement : Le nom du département (ex : Paris, Marseille, etc.). 

population_ref_cartographie : La population de référence pour la cartographie, probablement la population totale dans la zone donnée.

population_patho_cartographie : La population spécifiquement affectée par la pathologie dans la cartographie. Cela permet de comparer la population générale à la population ciblée par la pathologie.

effectif_1_inj_pathologie : Le nombre de personnes ayant reçu une première injection de vaccin pour chaque pathologie.

effectif_termine_pathologie : Le nombre de personnes ayant terminé leur vaccination pour la pathologie (par exemple, la série complète de doses).

taux_1_inj_pathologie : Le pourcentage de personnes ayant reçu la première injection pour chaque pathologie par rapport à la population de référence.

taux_termine_pathologie : Le pourcentage de personnes ayant terminé leur vaccination pour la pathologie par rapport à la population de référence.

ordre : Cette colonne pourrait être lié à l’ordre dans lequel les personnes sont vaccinées ou une hiérarchie des pathologies??

effectif_rappel_pathologie : Le nombre de personnes ayant reçu une injection de rappel pour la pathologie.

effectif_eligible_rappel_patho : Le nombre de personnes éligibles à l’injection de rappel pour la pathologie.

effectif_rappel_parmi_eli_patho : Le pourcentage de personnes ayant reçu une injection de rappel parmi celles éligibles.

taux_rappel_pathologie : Le pourcentage de personnes ayant reçu un rappel pour chaque pathologie.

taux_rappel_eligible_pathologie : Le taux de rappel parmi les personnes éligibles à ce rappel => indicateur d'adhésion au rappel parmi la population ciblée.

# Etude réalisée :

Dans un premier temps, nous avons fait le point sur le fichier et nous l'avons nettoyé afin de réaliser des analyses correctes.
Nous avons dans un second temps réalisé plusieurs analyses des données.

## Partie 1 :

## Partie 2 :

- Rapide comparaison de la distribution du taux de vaccination pour deux pathologies afin de faire l'état des lieux de la couverture vaccinale.
  
- Tracé du taux moyen de vaccination par pathologie => La dépendance aux opioïdes présente un taux inférieur aux autres.

  
- Tracé du taux moyen de vaccination par région => Les taux de vaccination plus faibles sont atteints au sein des départements d'Outre-mer.

  
- Tracé du taux moyen de vaccination par département (d'abord avec Outre-mer puis après seulement sur le territoire métropolitain) => mise en évidence d'un seuil à 90% et découverte que moins de vaccination dans le sud de la France et dans régions montagneuses.

  
- Scatterplot pour vérifier si la densité de population a une influence sur la couverture vaccinale=> cela ne semble pas être le cas.

  
- Comparaison du taux de vaccination initial (taux_1_inj_pathologie) par rapport au taux de vaccination complet (taux_termine_pathologie) afin de savoir si la série complète de dose est toujours respectée =>A nouveau les DOM sont plus fragiles, la Guyane possédant le taux de complétude de vaccin le plus faible.



<!-- #endregion -->
