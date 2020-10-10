# r_carto
Cours créés en 2018 pour le cours d'analyse de données et représentation cartographique, L3 Géographie Université Paris 1 Panthéon Sorbonne.

Contient des fiches de cours au format RMD pour apprendre à utiliser R, Rstudio et certaines packages en cartographie et analyse de données.

# Fiches cours 
Des cours et exercices au format RMD pour apprendre à utiliser R et Rstudio. 
Il es nécessaire d'installer R et Rstudio, puis d'ouvrir les RMD dans Rstudio

# Data
Les données tablulaires et géographiques à utiliser avec les fichier RMD lorsque cela est nécessaire.
A charger directement dans Rstudio. Les dataframes sont déjà prêts. Il n'est pas nécessaire de décompresser le fichier zip.
Pour les charger dans R, lancez la commande : load(unzip("presid2002_2017.zip", files="presid2002_2017.RData")). En spécifiant bien le chemin de "presid2002_2017.zip". Par exemple :
load(unzip("C:/Users/fbayer/CoursL3/presid2002_2017.zip", files="presid2002_2017.RData"))

Les fonds de carte sont au format RData, à charger avec la fonction load. 

# Guide_R.rmd
Les différentes fonctions utilisées dans les fiches de cours RMD. Simplifie la mise en application de certaines analyses (ACP, régression et cartographie des résidus). 
## TODO : ajout de fonctions communes

