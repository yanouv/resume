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
Critiques sur l’économie bleue

Depuis l’apparition du terme, l’« économie bleue » a rapidement été soutenue par les institutions internationales et de nombreux programmes pour faire de cette vision une réalité. On compte notamment des initiatives d’institutions (ONUAA, Banque Mondiale...) ou encore de fondations philanthropiques (Waitt Institute,…). La vision d’une « croissance » « soutenable » et « inclusive » a été promu lors de la conférence des Nations unies sur le développement durable 2012 (dite Rio+20). C’est aussi là que le concept s’est adjoint aux politiques de développement destinées aux PEID (petits États insulaires en développement). La réalité sur le terrain semble pourtant montrer que l’aspect « croissance » prend le pas sur la soutenabilité et l’inclusivité des populations locales. Le rapport du Transnational Institute, un think-tank, cite quelques exemples marquants :
- Au large de Kiribati (république insulaire d’Océanie), des permis pour l’exploitation minière en eaux profondes ont été délivrés alors que l’activité contribue à la dégradation de l’environnement et au réchauffement climatique. La région possède des ressources importantes en terres rares qui sont nécessaires à la transition aux énergies renouvelables (pour les batteries d’éoliennes, les panneaux photovoltaïques…), d’où son inclusion dans l’économie bleue.
- En Turquie, des changements réglementaires ont encouragé la concentration des exploitations dans l’aquaculture en bloquant les demandes de financement pour les petites exploitations plus traditionnelles.
La liste d’exemples est longue. Un tribunal indépendant international, rassemblant des tribunaux populaires de 5 pays autour de l’océan Indien, a émis un jugement spécial sur l’économie bleue :  accaparement illicite des biens communs océaniques et côtiers, marginalisation des communautés autochtones, destruction et dégradation des écosystèmes océaniques et côtiers...

Attention : ce qui est critiqué, ce n’est pas directement la dénomination technique d’« économie bleue » mais son statut d’étendard à une idéologie controversée.

Sources : Phillipa, 2025 ; TNI, 2019 ; International Independant Tribunal on Blue Economy, 2021.
</div>
Si chaque pays, chaque agence retient sa propre dénomination, on peut isoler un concept clé assez commun : l'économie maritime traite des activités économiques du secteur public et privé qui se déroulent directement ou indirectement dans l'océan et/ou la mer, reçoivent des produits de l'océan et/ou la mer et fournissent des biens et des services à l'océan et/ou la mer [Park and Kildow, 2014].

