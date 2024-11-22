# Projet-vaccination
Analyse exploratoire de données, Eugénie Porre et Solène Losantos


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

P
Nous avons réalisé plusieurs analyses du dataset. 

Idées de graphiques à tracer :

- Comparez les taux de vaccination entre différentes pathologies. Pathologies pour lesquelles le taux de vaccination est beaucoup plus élevé ou bas que pour d'autres ?

- examiner les taux de vaccination par région/ par département pour chaque pathologie.

- Le taux de vaccination initial (taux_1_inj_pathologie) par rapport au taux de vaccination complet (taux_termine_pathologie).

- Les taux de rappel et les niveaux d’éligibilité au rappel pour chaque pathologie, ce qui peut être utile pour cibler des campagnes de rappel.


