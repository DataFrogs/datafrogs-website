+++
title = "DataFrogs 2023.01"
description = "Conférence DataFrogs 2023.01, le 18 mars 2023."
author = "Rudi Bruchez"
date = "2023-01-10"
tags = ["sqlserver"]
categories = ["conference", "sqlserver"]
[[images]]
  src = "img/2023/datafrogs03.png"
  alt = "Vous êtes démasqué"
  stretch = "vertical"
+++

Inscrivez-vous sur [LinkedIn Events](https://www.linkedin.com/events/datafrogs2023-017018305962641874944/).

<!--more-->

## 18 mars 2023, en ligne

DataFrogs est une conférence communautaire gratuite sur Microsoft SQL Server.

Cette session aura lieu le samedi 18 mars en virtuel (lien fourni plus tard).

Inscrivez-vous sur LinkedIn Events pour obtenir les informations pratiques.

Les sessions seront disponibles pour tous, et concerneront principalement SQL Server on-premises ou sur Azure, le moteur relationnel, vous savez... 

## Programme

| Heure | Session | Qui |
| -------- | ------ | ------ |
| 09h00 | [Azure Synapse, en avant les pools]({{< relref path="#AzureSynapse" >}}) | [Sylvain Pagès, Devoteam](https://www.linkedin.com/in/sylvain-pag%C3%A8s-2b5170107/) |
| 10h15 | [SQL Server, les structures de données]({{< relref path="#SQLServerDonnees" >}}) | [Christophe Laporte, ConseilIt](https://www.linkedin.com/in/christophelaporte/) |
| 11h30 | [Les bonnes _mauvaises_ pratiques des groupes de disponibilité AlwaysOn]({{< relref path="#AlwaysOn" >}}) | [Amar Adghar, Microsoft](https://www.linkedin.com/in/amar-adghar-22b300155/) et [Stéphane Scherrer, Microsoft](https://www.linkedin.com/in/stephanescherrer/) |
| 13h30 | [Adoptez une approche Lakehouse pour vos projets BI avec Azure Synapse Analytics]({{< relref path="#Lakehouse" >}}) | [Sébastien Kobenan, Exakis Nelite](https://www.linkedin.com/in/sebastien-kobenan/) |
| 14h45 | [Les nouveautés SQL Server 2022]({{< relref path="#SqlServer2022" >}}) | [Julien Pierre, Microsoft](https://www.linkedin.com/in/julien-pierre-15782127/) |
| 16h00 | [Une histoire de mots... l'indexation textuelle]({{< relref path="#fts" >}}) | [Frédéric Brouard, SQL Spot](https://www.linkedin.com/in/frederic-brouard-alias-sqlpro-914761) et [Arian Papillon, Datafly, MVP](https://www.linkedin.com/in/arianpapillon/) |
| 17h15 | [SQL Server nostalgie]({{< relref path="#SQLServerNostalgie" >}}) | La communauté SQL Server francophone |
## Programme détaillé

### 09h00 &#10148; Azure Synapse, en avant les pools {#AzureSynapse}

[_Sylvain Pagès, Devoteam_](https://www.linkedin.com/in/sylvain-pag%C3%A8s-2b5170107/)

Avec l'arrivé d’Azure Synapse Analytics, nous avons à disposition des pools _Dedicated_ et _Serveless_.

On fait le tour sans casser d’œufs de poules ?

### 10h15 &#10148; SQL Server, les structures de données {#SQLServerDonnees}

[_Christophe Laporte, ConseilIt_](https://www.linkedin.com/in/christophelaporte/)

Tout développeur ou administrateur de bases de données devrait comprendre comment SQL Server accès aux données.

Cette session vous permettra de revoir les basiques sur le stockage des données, les différents types d’index, mais aussi d’évaluer leur usage au travers de DMV/DMF. Les nombreuses démonstrations permettront également de comprendre certains opérateurs des plans d’exécution.

### 11h30 &#10148; Les bonnes _mauvaises_ pratiques des groupes de disponibilité AlwaysOn {#AlwaysOn}

[_Amar Adghar, Microsoft_](https://www.linkedin.com/in/amar-adghar-22b300155/) et [_Stéphane Scherrer, Microsoft_](https://www.linkedin.com/in/stephanescherrer/)

Depuis dix ans, les Groupes de Disponibilité (AG pour Availability Groups) AlwaysOn permettent d’implémenter une haute disponibilité de qualité avec SQL Server.
Encore faut-il les installer et les gérer correctement.
Cela implique de comprendre le service de Cluster de Windows et les spécificités de cette fonctionnalité dans SQL Server.

Dans cette session, Stéphane Scherrer et Amar Adghar vous font bénéficier de leur expérience de terrain au sein de Microsoft pour vous aider à ne pas vous tromper sur les bonnes pratiques pour les AG.

Sujets abordés :

• Rappel des AG AlwaysOn, et fonctionnement du journal de transactions.
• Les bénéfices des AG sur les cluster de basculement (FCI) : HA+DR, auto-fix pages, DB level failure detection
• Retours d’expérience terrain
• Les points importants : Worker threads, copie des logins, maintenance AG aware.
• Interaction WSFC et AG
• Les fausses bonnes pratiques.

### 13h30 &#10148; Adoptez une approche Lakehouse pour vos projets BI avec Azure Synapse Analytics {#Lakehouse}

[_Sébastien Kobenan, Exakis Nelite_](https://www.linkedin.com/in/sebastien-kobenan/)

_Data Warehouse_ ou _Data Lake_ ?

Ne choisissez plus. Adoptez une approche Lakehouse.

Vous souhaitez construire une plateforme de données moderne dans votre entreprise ?
Vous connaissez les Data Warehouse, solution mature et éprouvée qui existe depuis maintenant plusieurs décennies ?
Vous avez aussi entendu parler des Data Lake, une approche qui s’est particulièrement popularisée au cours de la dernière décennie ?

Vous vous demandez quelle approche adopter ?

Dans cette session nous allons voir ensemble :

• Une architecture d’un projet BI avec une approche Data Warehouse
• Une architecture d’un projet BI avec une approche Data Lake
• Les avantages et les inconvénients de chacune des deux approches

Et surtout nous allons voir que vous pouvez avoir le meilleur des deux mondes avec une approche Lakehouse dans Azure Synapse Analytics.

### 14h45 &#10148; Les nouveautés SQL Server 2022 {#SqlServer2022}

[_Julien Pierre, Microsoft_](https://www.linkedin.com/in/julien-pierre-15782127/)

2022 a été marqué par de bien nombreux événements : Les élections présidentielles / La guerre en Ukraine / La mort de la reine d'Angleterre…  Et l'arrivée de SQL Server 2022 !

Quoi vous avez loupé ça !
Aller en route vers le cloud !
On embarque vers une vague de nouveautés au menu :

• Les nouveautés Query Store.
• Des nouveautés côté Moteur (_Built-in Query Intelligence_).
• Des nouveautés qui nous emmènent vers l'infini et au delà (le cloud).
• Des bonnes pratiques SQL (c'est toujours bien de revenir sur terre ).

Bref quelques trucs sympathiques à venir voir si vous ne les avez pas encore vu ;)

### 16h00 &#10148; Une histoire de mots... l'indexation textuelle {#fts}

[_Frédéric Brouard, SQL Spot_](https://www.linkedin.com/in/frederic-brouard-alias-sqlpro-914761) et [_Arian Papillon, Datafly, MVP_](https://www.linkedin.com/in/arianpapillon/)

S'il existe des outils externes comme Lucène/SOLR ou Elastic Search tous deux basés sur Java, il ne faut pas oublier que l'indexation textuelle est née des travaux des éditeurs de bases de données et a été consacrée par le comité de normalisation du langage SQL. Ainsi tous les SGBDR incorporent un outil de recherche textuelle plus ou moins conforme à la norme et plus ou moins performant.

Cette présentation à pour but de vous montrer comment réaliser une indexation textuelle des tables et documents électroniques par le biais de Microsoft SQL Server, la gérer, en tirer parti en effectuant des recherches textuelles ou sémantiques et enfin, d'en considérer les performances.

### 17h15 &#10148; SQL Server nostalgie {#SQLServerNostalgie}

Avec les vieux de la vieille de SQL Server, à micros ouverts.

Il paraît que la nostalgie est une mauvaise émotion. Mais ça fait du bien de temps en temps.
Venez suivre et partager vos anecdotes dans la dernière session de la journée, une session « apéro ».
Souvenirs, faits marquants, surprenants, intéressants ou drôles qui nous sont arrivés avec une fonctionnalité des anciennes versions de SQL Server.
