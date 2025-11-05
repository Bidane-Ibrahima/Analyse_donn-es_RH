# Reporting_RH
INTRODUCTION
KPIs_des_Salariées
Vous êtes RH et vous travaillez chaque jour avec de grandes quantités de données ? 
Vous avez certainement besoin de Power BI, sans même le savoir.

Voici un apercu des bénéfices du logiciel pour votre organisation :

Tous vos visuels interactifs et dynamiques : pyramide des âges, carte du monde, tableau de bord des effectifs, organigramme, vue globale de l’ensemble des salariés, analyse des écarts de salaire, tableau des entrées & sorties du personnel …

Analyse prédictive avec vos propres règles : simulateur de salaire Brut/net & annuel/mensuel, calculateur d’augmentation de salaire & inflation, prédiction de l'évolution de la masse salariale et du budget formation.

Vue High-level et précise pour chaque salarié.

Pour chaque salarié, Récap complet avec comparateur de salaire par rapport au global et à la même catégorie / même tranche Age.
1.ILLUSTRATION
![image_alt](https://github.com/Bidane-Ibrahima/Analyse_donn-es_RH/blob/main/Capture1.PNG?raw=true)
Je commence par ce que j’appelle la vue globale.
On retrouve ici un nuage de points représentant l’ensemble des salariés de l’entreprise. Les points bleus correspondent aux hommes, et les points roses aux femmes.
La ligne horizontale indique le salaire moyen de l’entreprise, qui, comme on peut le constater, est relativement élevé.

Grâce au curseur de zoom, je peux facilement naviguer vers des zones de salaires plus faibles ou plus élevés.
Il est également possible de filtrer les données pour afficher uniquement les hommes ou uniquement les femmes.
De la même façon, je peux zoomer sur les cadres ou sur l’ensemble du personnel.

Lorsque je passe la souris sur un point — par exemple sur un homme — une fiche récapitulative s’affiche, contenant les informations essentielles : le matricule, l’âge, la nationalité (avec le drapeau correspondant), le sexe, l’ancienneté et le salaire.
Ce dernier est représenté par une jauge colorée :

Si la jauge est verte, cela signifie que la personne gagne au-dessus du salaire moyen, avec un smiley souriant.

Si elle est jaune, la personne gagne en dessous du salaire moyen, et le smiley devient mécontent.

Enfin, si elle est rouge, cela indique un écart important par rapport au salaire moyen, et le smiley apparaît furieux.

Cet exemple illustre parfaitement les informations riches et interactives que l’on peut obtenir avec un reporting Power BI, simplement en survolant un point de données qui nous intéresse.
2.ILLUSTRATION
![image_alt](https://github.com/Bidane-Ibrahima/Analyse_donn-es_RH/blob/main/Capture2.PNG?raw=true)
Nous pouvons poursuivre la navigation dans ce reporting RH.
Je reviens donc sur la page d’accueil, et cette fois-ci, j’utilise le simulateur de salaire.
Ce type d’outil vous est peut-être familier : il permet de sélectionner un salaire brut annuel, par exemple 61 000 €, d’indiquer un taux d’imposition, ici 29 %, ainsi que le statut (par exemple cadre) et le nombre de mois de rémunération, dans ce cas 13 mois.

Une fois ces paramètres saisis, toutes les informations affichées sont recalculées automatiquement.
C’est un exemple d’analyse projective rendue possible grâce à Power BI, qui permet de simuler différents scénarios à partir de variables d’entrée telles que le salaire, le taux d’imposition ou le statut professionnel.

Ainsi, les résultats sont obtenus instantanément, offrant une visualisation en temps réel des impacts de chaque paramètre sur le revenu.
3.ILLUSTRATION
![image_alt](https://github.com/Bidane-Ibrahima/Analyse_donn-es_RH/blob/main/Capture3.PNG?raw=true)
c'est les salariés par région (nombre de salariés par split homme-femme par région)

4.ILLUSTRATION
![image_alt](https://github.com/Bidane-Ibrahima/Analyse_donn-es_RH/blob/main/Capture4.PNG?raw=true)

C'est la différence de salaire Homme-Femme
5.ILLUSTRATION
![image_alt](https://github.com/Bidane-Ibrahima/Analyse_donn-es_RH/blob/main/Capture5.PNG?raw=true)
On a les pyramides des anciénnetés et des agés par sexe Homme-Femme

6.ILLUSTRATION
![image_alt](https://github.com/Bidane-Ibrahima/Analyse_donn-es_RH/blob/main/Capture6.PNG?raw=true)

nOUS AVONS ICI le détail des salariés 

7.ILLUSTRATION
![image_alt](https://github.com/Bidane-Ibrahima/Analyse_donn-es_RH/blob/main/Capture7.PNG?raw=true)
Vous pouvez voir qu'on a toute les informations sur chaque salariés avec son numéros de matricule

8.ILLUSTRATION
![image_alt](https://github.com/Bidane-Ibrahima/Analyse_donn-es_RH/blob/main/Capture8.PNG?raw=true)
LA partie qui contient le résumé des sélariés

9.ILLUSTRATION
![image_alt](https://github.com/Bidane-Ibrahima/Analyse_donn-es_RH/blob/main/Capture9.PNG?raw=true)

Voici un autre exemple d’analyse projective réalisable avec Power BI.
Une vue particulièrement intéressante est celle du visuel en treemap, comparable à un camembert, qui permet d’observer la répartition des salariés selon différents critères.

Par exemple, on peut visualiser la proportion d’hommes et de femmes par nationalité, et constater qu’il existe une majorité de salariés français.
Cette répartition peut également être effectuée par catégorie professionnelle, type de contrat ou encore niveau de qualification.

De plus, il est possible d’affiner l’analyse à l’aide du visuel situé juste à côté, pour explorer plus en détail certaines dimensions des données.

En résumé, Power BI offre une visualisation dynamique et interactive, permettant d’explorer facilement les différentes composantes de la population salariale.

#CONCLUSION:
Le reporting RH que je viens de vous présenter a été entièrement conçu et développé par moi, Ibrahima Bidane, sur Power BI Desktop, un outil gratuit et extrêmement puissant.
Sur cet écran, vous pouvez voir un aperçu des différentes pages du rapport, ainsi que, sur la droite, l’ensemble des calculs et mesures nécessaires à son bon fonctionnement.

Par exemple, dans le dossier intitulé Calcul Effectif, j’ai regroupé toutes les formules DAX qui assurent la précision des indicateurs.
On y trouve notamment des mesures comme [Masse salariale totale ITD-1], construites à l’aide des fonctions CALCULATE et DATEADD.
Cela illustre bien que l’utilisation de Power BI est un véritable savoir-faire, qui demande rigueur, logique et expertise technique.

Au-delà des mesures, un tel rapport nécessite aussi une modélisation de données solide.
J’ai donc conçu une vue Modèle structurée autour de plusieurs tables :

des tables de faits, comme Fact Salarié ou Fact Différence Homme-Femme,

et des tables de dimensions, telles que Dim Contrat, Dim Catégorie ou encore Dim Date.

Enfin, aucune solution Power BI n’est complète sans une préparation minutieuse des données.
C’est pourquoi j’ai porté une attention particulière à la phase Power Query, qui assure la netteté, la cohérence et la fiabilité des données exploitées.

À travers ce projet, nous avons donc vu un exemple concret de reporting RH interactif et dynamique, où il est possible de naviguer à travers :

une carte du monde affichant les effectifs par continent et par pays,

ou encore un récapitulatif individuel apparaissant au simple survol d’un salarié.

Et ce que je vous ai montré aujourd’hui n’est qu’un aperçu des possibilités infinies que Power BI peut offrir à la fonction RH.

Pour toute formation, accompagnement ou création de reporting sur mesure,
👉 contactez-moi, Ibrahima Bidane — je me ferai un plaisir de vous aider à transformer vos données en véritables leviers de décision.

Vous pouvez trouver le fichier dans ce repositorie.


