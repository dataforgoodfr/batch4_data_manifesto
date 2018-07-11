## Je participe à un projet orienté "données"

#### interroger la **finalité** du projet, sa **légalité** et son possible **impact social et environnemental**.
#### faire mon possible pour que mes conditions de travail, en particulier le **temps de travail** qui m’est alloué, me permettent de mener avec les données un travail honnête et **le plus scientifique possible**.
#### veiller à ce que les **métriques à optimiser** soient pertinentes et **ne conduisent pas** le projet à avoir un impact social et environnemental négatif.


## Je collecte ou je dispose de données

#### ne pas collecter ou utiliser de **données inutilement personnelles et/ou sensibles**.
##### ... et une « donnée sensible » ?
  [L'article 9 du Règlement Général sur la Protection des Données (RGPD)](https://www.cnil.fr/fr/reglement-europeen-protection-donnees/chapitre2#Article9) prévoit que « le traitement des données à caractère personnel qui révèle l'origine raciale ou ethnique, les opinions politiques, les convictions religieuses ou philosophiques ou l'appartenance syndicale, ainsi que le traitement des données génétiques, des données biométriques aux fins d'identifier une personne physique de manière unique, des données concernant la santé ou des données concernant la vie sexuelle ou l'orientation sexuelle d'une personne physique sont interdits ».
  
#### ne pas collecter **des données dont je peux raisonnablement estimer qu’elles ne seront pas utiles** par rapport aux besoins du projet.
##### Le droit prévoit que les données personnelles doivent être sécurisées.
  L’[article 32 du Règlement Général sur la Protection des Données (RGPD)](https://www.cnil.fr/fr/reglement-europeen-protection-donnees/chapitre4#Article32) prévoit que des mesures techniques et organisationnelles doivent être mises en place afin d’assurer la sécurité des données personnelles.

#### ce que les données que je collecte ou dont je dispose soient **exactes** et que je comprenne bien leur signification. Pour cela, je m’engage à retracer autant que possible **l'origine** et le processus de création des données, ainsi que les éventuelles **modifications** qu'elles ont subies.
#### ne pas **négliger des données potentiellement utiles au projet**, dans la limite des principes éthiques, afin de ne pas mettre en péril la robustesse et la pertinence des résultats de leur traitement.
![](https://hippocrate.s3.eu-west-3.amazonaws.com/46313376580b4c44b6b1336de368dc52.png)
![](https://hippocrate.s3.eu-west-3.amazonaws.com/704b8234cc614fdc9e384c559c9d2ca1.png)
#### veiller à ce que les données dont j’ai la responsabilité soient **gérées et stockées en sécurité**.
#### **communiquer**, ou sinon rappeler aux équipes compétentes, la nécessité de communiquer auprès des personnes concernées, l’usage qui sera fait de leurs données, de **la façon la plus claire, explicite et transparente possible**.
#### veiller à ce que le **consentement des personnes** dont je collecte les données soit obtenu dans des conditions loyales et transparentes pour eux. En cas de changements ultérieurs des conditions d'utilisation, veiller à ce que ces changements leur soient aussi communiqués clairement et efficacement, et ré-obtenir leur consentement dans des conditions loyales, explicites et transparentes pour eux.



## Je prépare et j’explore les données

#### veiller, lorsque j'élimine ou j'impute des valeurs manquantes ou aberrantes, à **ne pas introduire de biais supplémentaires** qui mèneraient à des résultats partiels ou faux. Pour cela :
- je regarde la **distribution** des données à ma disposition ;
- je m'interroge sur **leurs potentiels biais**, notamment le biais de sélection ;
- je **justifie et documente** mon nettoyage.
#### ne pas créer de données caractéristiques (“features”) qui équivaudraient à des données personnelles sensibles si leur usage peut entraîner des effets discriminatoires illégaux ou illégitimes (exemples : code postal, nom de famille, ...).
#### 

## J'applique un ou des modèle(s) algorithmique(s)
#### déterminer le **meilleur compromis entre la performance et l'interprétabilité** sur l’ensemble des modèles à disposition et autant que possible, opter pour **les modèles les plus simples à expliquer aux personnes concernées** (un modèle performant permettra de diminuer les risques d’erreur tandis qu’un modèle interprétable permettra de mieux justifier les résultats du modèle).

![](https://hippocrate.s3.eu-west-3.amazonaws.com/46313376580b4c44b6b1336de368dc52.png)
![](https://hippocrate.s3.eu-west-3.amazonaws.com/733dbd0d476a4aea863e4da6cd24a824.png)
![](https://hippocrate.s3.eu-west-3.amazonaws.com/46313376580b4c44b6b1336de368dc52.png)
![](https://hippocrate.s3.eu-west-3.amazonaws.com/46313376580b4c44b6b1336de368dc52.png)

#### paramétrer et **tester plusieurs modèles** en ne m’arrêtant pas au premier modèle et paramétrage qui me semblent bons.
![](https://hippocrate.s3.eu-west-3.amazonaws.com/46313376580b4c44b6b1336de368dc52.png)
![](https://hippocrate.s3.eu-west-3.amazonaws.com/6a2325de422c4f2f9f2b7eb82850388c.png)
![](https://hippocrate.s3.eu-west-3.amazonaws.com/46313376580b4c44b6b1336de368dc52.png)

#### mesurer le **biais** et la **variance** pour contrôler l'exactitude et la dispersion du résultat et documenter les **métriques d'erreur** retenues.

#### garder un esprit critique par rapport aux **segments** issus d'un **algorithme de groupement** (“clustering”).
#### prévoir et prévenir les **dérives possibles dans le temps du modèle** par rapport aux données, de façon à éviter l'apparition de biais supplémentaires.

#### veiller à regarder les résultats dans leur ensemble (**non-partialité**) et à ne pas céder à un "**biais de confirmation**" (qui consisterait à voir ce à quoi je m'attendais). 

#### vérifier l’**absence de discrimination** : vérifier si le modèle s’applique avec la même pertinence sur des **segments potentiellement discriminatoires** de la population traitée.



## Je présente les résultats aux parties prenantes

#### communiquer ma démarche et mes résultats (ou leur absence) à mon client / mon équipe :
- en ne les **dénaturant** et en ne les **dissimulant pas**, notamment en choisissant une visualisation fidèle à l’ensemble des résultats
- en **garantissant la compréhension la plus exacte possible**, en optant pour les visualisations et explications les plus parlantes, en précisant les **précautions d’usage** à prendre avec ces résultats et leur interprétation.
![](https://hippocrate.s3.eu-west-3.amazonaws.com/46313376580b4c44b6b1336de368dc52.png)
![](https://hippocrate.s3.eu-west-3.amazonaws.com/b274b86d643440718773ec4c6d79fabd.png
)

#### donner **l'alerte** si je constate une utilisation frauduleuse, illégale, illégitime, discriminatoire ou non-éthique des résultats.

## Je termine le projet
#### veiller à ce que les données ne soient pas conservées **plus longtemps que ce qui est nécessaire** pour l’application telle que définie pendant le projet.
#### **documenter au maximum les données et leurs traitements** afin d’en garantir l’**explicabilité** et la **reproductibilité**.
#### anticiper les **usages** qui pourraient être faits de mon travail à moyen et long terme et faire mon possible pour garder sur lui un **droit de regard** et une **possibilité d’action**.
