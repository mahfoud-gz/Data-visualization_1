# Data-visualization_1

Les visualisations suivantes permettent d'explorer les possibilités dans l'utilisation de librairies Python (plus particulèrement matplotlib ici).
L'objectif est de reproduire le célèbre graphique du GapMinder avec les librairies Pandas et Matploltib (manipulation des données et visualisations).

La présentation par défaut est celle du croisement de l’espérance de vie à la naissance et du PIB par habitants, pour une grande majorité des États du monde. Les pays sont donc placés sur les deux axes selon leurs valeurs, et représentés par un cercle proportionnel à leur population pour l’année donnée. Une quatrième dimension d’information est apportée par la couleur de ces symboles qui, par défaut, signifie l’appartenance du pays à une une région du monde.

En premier lieu, voici cette représentation du GapMinder élaboré avec matplotlib (Python) : 

![alt text](https://github.com/mahfoud-gz/Data-visualization_1/blob/main/Data_viz_1_files/GapMinder.png?raw=true)

De plus, avec les données du nombre de population par pays, le graphique suivant est une visualisation dynamique, évoluant selon l'année, avec une projection du nombre de population jusqu'en 2100. De plus, pour conserver une cohérence, ces deux graphiques adoptent le même code couleur par continent : Asie (rouge), Europe (jaune), Afrique (bleu), Amérique (vert). 

![alt text](https://github.com/mahfoud-gz/Data-visualization_1/blob/main/Data_viz_1_files/Bar_chart_race_population.gif)
