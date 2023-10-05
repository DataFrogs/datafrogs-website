+++
title = "DataFrogs 2023.02"
description = "Conférence DataFrogs 2023.02, le 14 octobre 2023."
author = "Rudi Bruchez"
date = "2023-10-04"
tags = ["sqlserver"]
categories = ["conference", "sqlserver"]
[[images]]
  src = "img/2023/datafrogs03.png"
  alt = "Vous êtes démasqué"
  stretch = "vertical"
+++

**Inscrivez-vous sur [LinkedIn Events](https://www.linkedin.com/events/datafrogs2023-027094267767230513152/)**.

<!--more-->

## 4 octobre 2023, le matin, en ligne

DataFrogs est une conférence communautaire gratuite sur Microsoft SQL Server.

Cette session aura lieu le samedi 4 octobre 2023 au matin, en virtuel (lien fourni plus tard).

Inscrivez-vous sur [LinkedIn Events](https://www.linkedin.com/events/datafrogs2023-027094267767230513152/) pour obtenir les informations pratiques.

Il y aura cette fois-ci quatre sessions, la conférence se tiendra donc sur une demi-journée, le matin.

Les sessions seront disponibles pour tous, et concerneront principalement SQL Server on-premises ou sur Azure, le moteur relationnel, vous savez...

## Programme

| Heure | Session | Qui |
| -------- | ------ | ------ |
| 09h00 | [SQL Server Hybride Azure]({{< relref path="#Hybride" >}}) | [Stéphane Scherrer, Microsoft](https://www.linkedin.com/in/stephanescherrer/) et [Sylvain Pagès, Devoteam](https://www.linkedin.com/in/sylvain-pag%C3%A8s-2b5170107/) |
| 10h15 | [La gestion des droits dans SQL Server]({{< relref path="#Privileges" >}}) | [Sébastien Kobenan](https://www.linkedin.com/in/sebastien-kobenan/) |
| 11h30 | [Migrer un groupe de disponibilité AlwaysOn sans perte du cluster]({{< relref path="#AlwaysOn" >}}) | [Amar Adghar, Microsoft](https://www.linkedin.com/in/amar-adghar-22b300155/) et [Stéphane Scherrer, Microsoft](https://www.linkedin.com/in/stephanescherrer/) |
| 13h30 | [Adoptez une approche Lakehouse pour vos projets BI avec Azure Synapse Analytics]({{< relref path="#Lakehouse" >}}) | [Sébastien Kobenan, Exakis Nelite](https://www.linkedin.com/in/sebastien-kobenan/) |
| 14h45 | [Les nouveautés SQL Server 2022]({{< relref path="#SqlServer2022" >}}) | [Julien Pierre, Microsoft](https://www.linkedin.com/in/julien-pierre-15782127/) et [Pascal Deliot, Microsoft](https://www.linkedin.com/comm/in/pascal-deliot-332454) |
| 16h00 | [Une histoire de mots... l'indexation textuelle]({{< relref path="#fts" >}}) | [Frédéric Brouard, SQL Spot](https://www.linkedin.com/in/frederic-brouard-alias-sqlpro-914761) et [Arian Papillon, Datafly, MVP](https://www.linkedin.com/in/arianpapillon/) |
| 17h15 | [SQL Server nostalgie]({{< relref path="#SQLServerNostalgie" >}}) | La communauté SQL Server francophone |
## Programme détaillé

### 09h00 &#10148; SQL Server Hybride Azure {#Hybride}

[_Stéphane Scherrer, Microsoft_](https://www.linkedin.com/in/stephanescherrer/) et [_Sylvain Pagès, Devoteam_](https://www.linkedin.com/in/sylvain-pag%C3%A8s-2b5170107/)

Même si vous voulez garder les données chez vous, l’hybridation vous permet d’ouvrir de nouveaux horizons avec SQL Server 2022.

Sujets abordés :

- Ce qu’apporte SQL Server 2022.
- C’est quoi l’hybride ?
- Les tableaux de bords globaux et les outils pour se simplifier la vie.
- Les modes d’hybridation.
- Quelques scénarios simples comme le stockage des données froides (sans stretch data) et le DR.
- Interroger les données en langage naturel.

### 10h15 &#10148; La gestion des droits dans SQL Server {#Privileges}

[_Sébastien Kobenan_](https://www.linkedin.com/in/sebastien-kobenan/)

Lorsqu'on débute sur SQL Server, on est souvent perdu dans la gestion des permissions.

On découvre des notions comme serveur, login, user ou role et on ne sait pas toujours les différencier ni dans quelles situations les utiliser.

Je vous propose dans cette session de revenir sur les bases de la sécurité dans SQL Server.

Nous verrons :

- la différence entre un serveur de base de données, une base de données et un schéma.
- la différence entre un login, un user et un rôle
- comment attribuer ou refuser des droits à un utilisateur

Si le temps nous le permet, nous verrons en bonus, les modes d'authentification dans SQL Server et surtout l'authentification Azure AD dans SQL Server 2022.

 ### 11h30 &#10148; Les bonnes _mauvaises_ pratiques des groupes de disponibilité AlwaysOn {#AlwaysOn}

[_Amar Adghar, Microsoft_](https://www.linkedin.com/in/amar-adghar-22b300155/) et [_Stéphane Scherrer, Microsoft_](https://www.linkedin.com/in/stephanescherrer/)

Depuis dix ans, les Groupes de Disponibilité (AG pour Availability Groups) AlwaysOn permettent d’implémenter une haute disponibilité de qualité avec SQL Server.
Encore faut-il les installer et les gérer correctement.
Cela implique de comprendre le service de Cluster de Windows et les spécificités de cette fonctionnalité dans SQL Server.

Dans cette session, Stéphane Scherrer et Amar Adghar vous font bénéficier de leur expérience de terrain au sein de Microsoft pour vous aider à ne pas vous tromper sur les bonnes pratiques pour les AG.

Sujets abordés :

- Rappel des AG AlwaysOn, et fonctionnement du journal de transactions.
- Les bénéfices des AG sur les clusters de basculement (FCI) : HA+DR, auto-fix pages, DB level failure detection.
- Retours d’expérience terrain.
- Les points importants : Worker threads, copie des logins, maintenance AG aware.
- Interaction WSFC et AG.
- Les fausses bonnes pratiques.

### 13h30 &#10148; Adoptez une approche _Lakehouse_ pour vos projets BI avec Azure Synapse Analytics {#Lakehouse}

[_Sébastien Kobenan, Exakis Nelite_](https://www.linkedin.com/in/sebastien-kobenan/)

_Data Warehouse_ ou _Data Lake_ ?

Ne choisissez plus. Adoptez une approche _Lakehouse_.

Vous souhaitez construire une plateforme de données moderne dans votre entreprise ?
Vous connaissez les _Data Warehouse_, solution mature et éprouvée qui existe depuis maintenant plusieurs décennies ?
Vous avez aussi entendu parler des _Data Lakes_, une approche qui s’est particulièrement popularisée au cours de la dernière décennie ?

Vous vous demandez quelle approche adopter ?

Dans cette session nous allons voir ensemble :

- Une architecture d’un projet BI avec une approche _Data Warehouse_.
- Une architecture d’un projet BI avec une approche _Data Lake_.
- Les avantages et les inconvénients de chacune des deux approches.

Et surtout nous allons voir que vous pouvez avoir le meilleur des deux mondes avec une approche _Lakehouse_ dans Azure Synapse Analytics.

### 14h45 &#10148; Les nouveautés SQL Server 2022 {#SqlServer2022}

[_Julien Pierre, Microsoft_](https://www.linkedin.com/in/julien-pierre-15782127/) et [_Pascal Deliot, Microsoft_](https://www.linkedin.com/comm/in/pascal-deliot-332454)

2022 a été marqué par de bien nombreux événements : Les élections présidentielles / La guerre en Ukraine / La mort de la reine d'Angleterre…  Et l'arrivée de SQL Server 2022 !

Quoi vous avez loupé ça !
Aller en route vers le cloud !
On embarque vers une vague de nouveautés au menu :

- Les nouveautés Query Store.
- Des nouveautés côté Moteur (_Built-in Query Intelligence_).
- Des nouveautés qui nous emmènent vers l'infini et au delà (le cloud).
- Des bonnes pratiques SQL (c'est toujours bien de revenir sur terre ).

Bref quelques trucs sympathiques à venir voir !

