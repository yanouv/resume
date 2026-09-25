---
title: "Revue de la Litterature"
math: true
authors:
- me
date: "2025-07-04T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-04T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication metadata — structured fields used by citation styles and BibTeX export.
# Preprints typically have no formal venue; omit `publication` until the work is accepted.

abstract: This work examines the monetary policy trade-offs surrounding Hungary’s exceptionally rapid disinflation of 2023. Using an IMF Quarterly Projection Model calibrated to the Hungarian economy, we conduct a forecasting exercise to assess whether a looser policy stance could have produced a softer landing, and ultimately a case of “painless disinflation”. The model forecast reproduces a rapid decline in inflation while allowing the nominal policy rate to decrease progressively. The interaction between the interest- and exchange-rate channels, coupled with the decline in inflation expectations tighten the monetary conditions. Our alternative policy simulations indicate more aggressive policy rules can marginally improve inflation outcomes, but at the expense of a larger negative output gap. 

# Summary. An optional shortened abstract.
summary: "A QPM Analysis of Hungary’s Post-2022 Inflation Episode"

tags:
- Matlab
- New Keynesian

featured: true

hugoblox:
  ids:
    arxiv: 

links:
- type: pdf
  provider: arxiv
  id: 1512.04133v1
- type: code
  url: https://github.com/HugoBlox/kit
- type: dataset
  url: "#"


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Bloomberg**](https://infostart.hu/images/site/articles/lead/2024/04/1713871840-cufL4MkDU_md.jpg)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
## Introduction

L’économie maritime est une composante essentielle de l’économie mondiale. De la pêche et du tourisme à l’énergie offshore et au transport maritime, elle soutient des millions d’emplois dans des secteurs et des régions très variés. Pourtant, il n’existe pas de vision partagée à l’échelle internationale de ses contours et du nombre de personnes employées dans l’économie de la mer. En France, l’Insee n’est pas le seul service statistique à s’intéresser au sujet et sa méthodologie se confronte régulièrement aux positions/considérations divergentes des acteurs locaux, ce qui limite la comparabilité et la complémentarité des études. 
Les raisons de cette absence de normes sur ce qu’est l’économie maritime, son étendue et les méthodes d’estimation constituent la première partie de cette revue de littérature. Dans un second temps sont étudiées les facteurs susceptibles d’influencer tant le volume d’emplois que leurs caractéristiques et de mettre en lumière les potentielles futures transformations du marché du travail dans ce secteur.


## Partie 1 : Qu’est-ce que l’économie maritime ?

Cette partie est consacrée à l’exploration du terme d’économie maritime. L’approche est progressive : on part de l’analyse même de l’expression, puis on en identifie les secteurs. Enfin, on rend compte des méthodologies possibles pour étudier ce secteur. L’intérêt de cette partie est notamment de mettre en valeur les divergences internationales et la diversité des points de vue. 

### A - Définir l’« économie maritime »

L’Insee désigne par « économie maritime » les activités utilisant les ressources marines ou qui ne pourraient exister sans la mer. Cette définition est le résultat d’un consensus avec le SDES et elle se base sur celle de l’Ifremer. Aujourd’hui, il n’existe pourtant pas de dénomination commune à ce que l’on appelle « économie maritime » dans le monde. Bien au contraire, on trouve une constellation de termes différents pour parler de ce secteur : économie maritime, blue economy, ocean & coastal economy, maritime industry, marine economy… Aujourd’hui, le plus populaire est l’« économie bleue » (cf. table 2) ;  notamment parce qu’il a été mis en avant par le gouvernement américain [U.S. Senate Committee on Commerce, Science, and Transportation, 2009] et la Commission européenne [European Commission, 2012], puis repris ensuite par les grandes institutions internationales (Banque mondiale, Nations Unies…) et les chercheurs. Cependant, l’usage du terme « économie bleue » n’est pas neutre :
- d’une part, il ne suppose rien sur la méthodologie et la classification des activités de l’économie maritime ;
- d’autre part, il a été proposé initialement par un industriel belge pour discuter d’une croissance soutenable et inclusive. Mais l’inclusion de secteurs polluants dans la définition (gaz et pétrole offshore), les acteurs impliqués (industriels et institutions économiques internationales) et le contexte d’émergence du terme (en pleine sortie de la crise de 2008) lui ont valu des critiques. L’expression « économie bleue » était alors mobilisée de façon quasi indissociable avec la notion de « croissance bleue »1. 
<div style="border: 2px solid #555; padding: 10px; border-radius: 8px; background-color: #f9f9f9;">
_Critiques sur l’économie bleue_

Depuis l’apparition du terme, l’« économie bleue » a rapidement été soutenue par les institutions internationales et de nombreux programmes pour faire de cette vision une réalité. On compte notamment des initiatives d’institutions (ONUAA, Banque Mondiale...) ou encore de fondations philanthropiques (Waitt Institute,…). La vision d’une « croissance » « soutenable » et « inclusive » a été promu lors de la conférence des Nations unies sur le développement durable 2012 (dite Rio+20). C’est aussi là que le concept s’est adjoint aux politiques de développement destinées aux PEID (petits États insulaires en développement). La réalité sur le terrain semble pourtant montrer que l’aspect « croissance » prend le pas sur la soutenabilité et l’inclusivité des populations locales. Le rapport du Transnational Institute, un think-tank, cite quelques exemples marquants :
- Au large de Kiribati (république insulaire d’Océanie), des permis pour l’exploitation minière en eaux profondes ont été délivrés alors que l’activité contribue à la dégradation de l’environnement et au réchauffement climatique. La région possède des ressources importantes en terres rares qui sont nécessaires à la transition aux énergies renouvelables (pour les batteries d’éoliennes, les panneaux photovoltaïques…), d’où son inclusion dans l’économie bleue.
- En Turquie, des changements réglementaires ont encouragé la concentration des exploitations dans l’aquaculture en bloquant les demandes de financement pour les petites exploitations plus traditionnelles.
La liste d’exemples est longue. Un tribunal indépendant international, rassemblant des tribunaux populaires de 5 pays autour de l’océan Indien, a émis un jugement spécial sur l’économie bleue :  accaparement illicite des biens communs océaniques et côtiers, marginalisation des communautés autochtones, destruction et dégradation des écosystèmes océaniques et côtiers...

Attention : ce qui est critiqué, ce n’est pas directement la dénomination technique d’« économie bleue » mais son statut d’étendard à une idéologie controversée.

Sources : Phillipa, 2025 ; TNI, 2019 ; International Independant Tribunal on Blue Economy, 2021.
</div>
Si chaque pays, chaque agence retient sa propre dénomination, on peut isoler un concept clé assez commun : l'économie maritime traite des activités économiques du secteur public et privé qui se déroulent directement ou indirectement dans l'océan et/ou la mer, reçoivent des produits de l'océan et/ou la mer et fournissent des biens et des services à l'océan et/ou la mer [Park and Kildow, 2014].

![Description of image](image1.png "Source : suggestion d’illustration tirée de [Park et Kildrow, 2014]")

Néanmoins, quelques divergences subsistent quant au champ d’application de l’économie maritime :
-  Les comparaisons internationales sont relativement limitées, car les classifications des entreprises changent complètement d’un pays à l’autre
- L’Ifremer classe les centrales à combustibles fossiles et nucléaires et les éoliennes dans l'économie maritime, ce qui n'est le cas d'aucun autre pays. Cette catégorisation découle de l'hypothèse selon laquelle les unités de production d'électricité sont situées sur les côtes.
- Les États-Unis incluent les Grands Lacs au-contraire du Canada
- L’Australie exclut le secteur public

Les énoncés des différentes définitions à travers le monde sont reportées dans le tableau suivant [Park and Kildow, 2014] :

![Description of image](image2.png)

Le débat sur la dénomination de l’« économie maritime » est essentiellement technique. Le choix de l’expression est pratique avant d’être scientifique ou idéologique et impacte généralement peu le cœur de sujet des études. Un accord au niveau supranational serait pourtant bénéfique pour la clarté.
**[...]**

### B – Les secteurs de l’économie maritime

Une classification de l’ensemble des secteurs de l’économie maritime est tout de même plus aisée pour prendre conscience de l’ampleur de ce pan de l’économie. Voici, par exemple la classification de l’Ifremer :

| **Secteurs**  | **Catégories** |
| ----- | --- |
| Secteur industriel |   |
| Produits de la mer   | Pêche marine, aquaculture marine (pisciculture et
conchyliculture), production d'algues, marchés aux poissons et commerce du poisson,
industrie de transformation des produits de la mer  |
|Extraction de granulats marins |Sables et graviers siliceux, sables et sédiments calcaires|
|Production d'électricité|Centrales électriques conventionnelles à combustibles fossiles, centrales nucléaires, éoliennes Construction et réparation navales Construction de ports, de barrages, de digues et de canaux navigables, équipement naval et construction de bateaux Centrales nucléaires, Éoliennes|
|Construction et réparation navales|Construction et réparation de navires marchands et militaires, armement naval et construction de bateaux|
|Génie civil maritime et fluvial|Construction de ports, de barrages, de digues, de canaux navigables, de réserves d'eau, d'écluses et d'autres installations de régulation des cours d'eau / Exécution des travaux : en eau (construction de batardeaux, construction des piles de ponts), dragage, sous-marin (par plongeur ou autres moyens) / Nettoyage des tranchées et aménagement des berges et coupe des herbes aquatiques|
|Câbles sous-marins|Fabrication, pose et entretien de câbles sous-marins immergés en profondeur et, en général, enterrés, destinés à transporter des communications ou de l'énergie électrique|
|Industrie pétrolière et gazière offshore|Fourniture de services et d'équipements liés au pétrole et au gaz dans les domaines de l'exploration et de la production, du raffinage et de la pétrochimie|
|Tourisme littoral|Dépenses des touristes résidents et non-résidents dans les activités touristiques caractéristiques : dépenses d'hébergement, de restauration, de forfaits tout compris (pour les non-résidents), dépenses liées aux séjours : dépenses alimentaires, achats divers, déplacements sur place (taxi ou transports en commun), services aux particuliers, loyers fictifs|
|‍Transports maritimes et fluviaux|Exploitation et organisation générale des ports, Services portuaires aux navires et aux marchandises|
|‍Assurances maritimes|Assurances maritimes et banques|
|‍Secteur public non marchand|     |
|‍Marine nationale, Défense nationale|Intervention publique Économique et sociale (régime social des marins, protection sociale), Réglementation et éducation|
|‍Protection de l'environnement côtier et marin|Prévention, réduction et élimination des pollutions ; la réparation
des dommages et l'acquisition, le traitement et la circulation de l'information sur l'environnement|
|‍Recherche marine|Activités des organismes publics français dans le domaine de la recherche marine et de l'océanographie opérationnelle|

Dans ce tableau, plusieurs secteurs se distinguent.

Le tourisme littoral est le 1er poste de l’emploi de l’économie maritime en région PACA en représentant près de 70 % des emplois concernés [Insee, 2017]. Pourtant, de nombreuses études ne l’inclut pas, c’est notamment le cas du CMF (Cluster Maritime Français). L’ouvrage collectif Mare economicum reconnaît ainsi que « le tourisme littoral est curieusement assez peu analysé par les économistes malgré son poids économique de premier plan, peut-être en raison de son caractère pluriel qui le rend si difficile à appréhender » [Guillotreau, 2008]. En effet, le tourisme a une caractéristique propre : on considère une activité comme touristique non pas en fonction de la production mais en fonction de sa clientèle. Or, de nombreuses activités ne dépendent pas que du tourisme pour fonctionner. Comment alors définir cette part touristique, pour un restaurant qui accueille dans la même journée des habitants locaux et des touristes ou pour un hôtel qui héberge des voyageurs d’affaires et des vacanciers ? De plus, des estimations exactes sont difficilement réalisables, l’activité touristique étant périodique et les PME-TPE en nombre important. La question est encore plus délicate si on veut s’intéresser au tourisme littoral. Comment isoler l’activité touristique liée à la mer dans des communes qui proposent également des activités qui ne sont pas maritimes (ex : festival, musées…) ? **[...]**

Or, en raison de l’ampleur du tourisme, des choix méthodologiques divergents peuvent avoir un impact conséquent sur l’estimation du volume d’emploi.

La Marine nationale est aussi un secteur unique en raison de son poids important (2ᵉ poste d’emploi [Insee, 2017]) et des rares données accessibles. En effet, seul le Ministère des Armées diffuse des informations sur le corps militaire français en raison du secret Défense. Les publications sur l’effectif de la Marine nationale et sa composition sont sporadiques, tant en matière de régularité que de contenu. Difficile donc de mener des analyses poussées sans un accord avec la Défense.
Enfin, ce tableau n’est pas complet. Il reste des activités méconnues ou dont il est difficile de quantifier l’aspect maritime. Dans le secteur de la culture, la réalisation de films et de livres autour de la mer et de l’océan mobilisent des équipes employées par des sociétés de production et d’édition qui ne sont pas spécialisés dans l’environnement maritime. On pourrait aussi ajouter les data centers, qui s’installe au bord de mer pour refroidir les serveurs. On en recense 19 en PACA dont 5 installés dans le port de Marseille-Fos. Leur inclusion suivrait la même logique que celle des centrales électriques.

### C – La méthodologie de l’économie maritime

Jusqu’à présent, nous avons observé comment les services statistiques à travers le monde définissent ce à quoi doit correspondre l’économie maritime. Il vient maintenant le temps de confronter ce premier travail à la réalité du secteur. Le choix de la méthodologie est déterminant car elle influe grandement sur ce qu’il y aura dans la base de données. 

Globalement, les instituts de statistiques publiques s’appuient tous sur un système de nomenclature des entreprises : en France, c’est la NAF. Cette nomenclature permet d’isoler déjà tous les emplois qui intègrent clairement une composante maritime, car leurs désignations portent les mots « nautique », « marin » ou encore « portuaire ». 

Cependant, l’un des grands enjeux de la méthodologie est de déterminer quelles sont les activités « partiellement maritimes », c’est-à-dire celles qui appartiennent au périmètre de l’économie maritime sans en constituer le cœur d’activité. Par exemple, l’activité d’une cimenterie n’est pas maritime a priori, l’activité « fabrication de ciment » n’ayant pas de lien avec les ressources marines. Cependant, si ladite cimenterie participe à la construction de fondations gravitaires pour les éoliennes offshore, elle a un lien avec l’économie maritime.

Plusieurs approches sont possibles :
- **[...]**
- L’exploitation du TES (Tableaux Entrées-Sorties) :
<div style="border: 2px solid #555; padding: 10px; border-radius: 8px; background-color: #f9f9f9;">
Le tableau des entrées-sorties (TES) est l’un des outils des comptes nationaux. Il analyse chacun des produits de la nomenclature NAF selon son origine (production nationale ou importations) et sa destination (consommation intermédiaire, consommation finale, exportations, investissements). Pour chaque produit, le TES établit l’équilibre comptable entre ressources et emploi. En anglais, on parle d’input-output tables ou de supply-use tables. Ce tableau est publié chaque année par l’Insee.
Source : CESER, 2014.
</div>
Le Nomura Research Institute au Japon se base sur une analyse input-output et établit qu’une entreprise appartient au périmètre de l’« industrie maritime » si plus de 10 % des intrants d’une industrie sont utilisés pour des activités en lien avec la mer [NRI, 2009 (non-disponible en ligne)].

Le NOEP (puis le BEA son sucesseur) aux États-Unis effectue un premier filtrage géographique des activités « potentiellement maritimes » si le code postal est associé à au plus un comté « shore-adjacent » au rivage [méthodologie du NOEP rédigée par Colgan, 2007]. Ainsi, les codes postaux ont été modifiés pour identifier les zones cotières après le Coastal Zone Management Act [NOAA, 1972].
<div style="border: 2px solid #555; padding: 10px; border-radius: 8px; background-color: #f9f9f9;">
Les zones côtières aux États-Unis

La définition de l’économie côtière de NOEP repose sur une approche par paliers. Les définitions des niveaux sont basées sur les codes postaux et les limites des comtés. Les catégories suivantes sont utilisées en commençant par le littoral et en poursuivant vers l’intérieur des terres :
- Near-Shore : établissements ou population situés dans un code postal immédiatement adjacent à un océan, à un grand lac ou à une rivière ou une baie inclus·e.
- Shore-Adjacent Coastal Zone County : comtés jouxtant en totalité ou en partie par la zone côtière d’un État selon la loi de 1972 sur la gestion de la zone côtière (Coastal Zone Management Act), telle que définie par cet État, et qui est adjacent à un océan, à un grand lac ou à un fleuve ou une baie inclus·e. Cela inclut les codes postaux proches du rivage.
- Non–shore-Adjacent Coastal Zone County : comté jouxtant en totalité ou en partie par la zone côtière d’un État selon la loi de 1972 sur la gestion de la zone côtière, telle que définie par cet État, et qui n’est pas adjacent à un océan, à un grand lac, ou à une rivière ou une baie inclus·e.
- Coastal Zone Counties : comtés composés de comtés adjacents au rivage et de comtés non adjacents au rivage.
- Non-Coastal Zone Watershed County : comté situé en dehors de la zone côtière, mais à l’intérieur d'un bassin versant côtier.
- Coastal Watershed County : un comté situé dans un bassin versant côtier tel que défini par l’U.S. Geological Survey. Les comtés du bassin versant comprennent tous les comtés de la zone côtière et les comtés du bassin versant qui ne sont pas situés dans la zone côtière.
- Inland County : comté situé en dehors d’un bassin versant côtier.

Source : méthodologie du NOEP, 2007.
</div>

Une fois réalisé ce premier filtrage, le BEA analyse le TES pour identifier les consommations intermédiaires (en entrées) et la marchandise produite (en sortie) qui sont liées à l’économie maritime. Si seule une partie de la production était pertinente pour l'économie maritime, des données supplémentaires étaient nécessaires pour identifier la composante maritime. L'aquaculture est un exemple : l'aquaculture marine a dû être séparée de l'aquaculture d'eau douce, et les données du NOAA Fisheries ont été utilisées pour déterminer la part correcte et l’ajouter à la base de données. 

Pour déterminer la valeur ajoutée, l’emploi et les salaires, les TES donnent des informations à un niveau d’agrégation qui ne permet de distinguer l’économie maritime au sein des industries. L’hypothèse est donc faite que le volume d’emploi, la valeur ajoutée, les salaires […] correspondent à l’application de notre part d’activité maritime précédemment calculée comme un pourcentage des valeurs totales de l’industrie (référencées dans le TES).

Cette hypothèse est assez commune dans les analyses mobilisant un TES, notamment dans la recherche. Des chercheurs polonais [Kwiatkowski et Zaucha, 2023] ont essayé d’appliquer la définition de la Commission européenne avec la nomenclature locale. Ils classifient les activités maritimes en quantifiant l’emploi maritime d’un secteur à partir de la valeur ajoutée des entreprises. Ils considèrent ensuite que la part de la VA des entreprises du secteur dans les régions côtières par rapport à la totalité du pays représente la part de l’emploi du secteur comme faisant partie de l’économie maritime. Petite spécificité : ils ont utilisé les bases de données international Eurostat SBS et Orbis. 

- On trouve encore d’autres méthodes, certains chercheurs utilisent des modèles où le périmètre est prédéfini (on retrouve ce cas dans [Hynes et al., 2021] dans un modèle de microsimulation spatial ou dans [Liang et al., 2025] avec des TES).
- 
Enfin, cette liste n’est qu’un aperçu. Elle est non-exhaustive car beaucoup n’explicitent pas leurs techniques de manière précise. Il existe sûrement d’autres méthodologies, qui peuvent combiner les approches précédentes ou utiliser des outils complètement différents.

Surtout, on peut encore caractériser les emplois « induits » par l’économie maritime, dont l’existence peut dépendre des activités maritimes. Par exemple, la valeur ajoutée du secteur de la construction et de la réparation navales est générée par des activités en amont et en aval de la chaîne d'approvisionnement de l'industrie. Cela indique qu'au-delà de la contribution directe du secteur à l'économie maritime, il peut y avoir des effets multiplicateurs significatifs sur le revenu et l'emploi dans d’autres segments de l'économie. L’inclusion des emplois induits est discutable mais elle permet de mieux apprécier l’influence global de la présence de la mer/l’océan sur un territoire.
