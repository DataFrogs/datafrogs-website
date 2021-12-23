+++
title = "DataFrogs 2022.01"
description = "Conférence DataFrogs 2022.01, le 15 janvier 2022."
author = "Rudi Bruchez"
date = "2021-12-21"
tags = ["sqlserver"]
categories = ["conference", "sqlserver"]
[[images]]
  src = "img/2021/12/datafrogs01.png"
  alt = "Vous êtes démasqué"
  stretch = "vertical"
+++

Inscrivez-vous sur [LinkedIn Events](https://www.linkedin.com/events/datafrogs2022-016866712325664120832/).

<!--more-->

## 15 janvier 2022, en ligne

DataFrogs est une conférence communautaire gratuite sur Microsoft SQL Server.

Cette session aura lieu le samedi 15 janvier en virtuel (lien fourni plus tard).

Inscrivez-vous sur LinkedIn Events pour obtenir les informations pratiques.

Les sessions seront disponibles pour tous, et concerneront principalement SQL Server on-premises ou sur Azure, le moteur relationnel, vous savez... 

Il n'y aura aucun "Power..." dans ces sessions, c'est garanti !

## Programme

Heure | Session | Qui
-------- | ------ | ------
09h00 | [Stockage SQL, virtualisation et performances]({{< relref path="#session01" >}}) | [David Barbarin, Migros Online](https://www.linkedin.com/in/mikedavem/)
10h15 | [Les groupes de disponibilité AlwaysOn par la pratique]({{< relref path="#session02" >}}) | [Christophe Laporte](https://www.linkedin.com/in/christophelaporte/)
11h30 | [Je veux migrer mes bases dans Azure MAIS …]({{< relref path="#session03" >}}) | [Julien Pierre, Microsoft](https://www.linkedin.com/in/julien-pierre-15782127/) et [Sylvain Pagès](https://www.linkedin.com/in/sylvain-pag%C3%A8s-2b5170107/)
13h30 | [Gérer les bases de données à forte volumétrie]({{< relref path="#session04" >}}) | [Arian Papillon, Datafly, MVP](https://www.linkedin.com/in/arianpapillon/)
14h45 | [SQL Server sur Google Cloud Platform]({{< relref path="#session05" >}}) | [Clément Hugé](https://www.linkedin.com/in/clementhuge/)
16h00 | [Simplifier vos projets BI grâce à Azure Data Factory]({{< relref path="#session06" >}}) | [Sébastien Kobenan](https://www.linkedin.com/in/sebastien-kobenan/)
17h15 | [Query Store, bientôt incontournable ?]({{< relref path="#session07" >}}) | [Steven NAUDET, DBI Services](https://www.linkedin.com/in/steven-naudet-aa540158/)

## Programme détaillé

### 09h00 &#10148; Stockage SQL, virtualisation et performances {#session01}

[David Barbarin, Migros Online](https://www.linkedin.com/in/mikedavem/)

Virtualiser SQL Server avec VMWare est devenue monnaie courante depuis quelques années. Rare sont devenues les infrastructures dites uniquement Bar Metal. Quid de la performance avec une instance SQL Server dans ce cas? Est-ce que virtualisation rime avec performance? Quelles considérations à avoir lorsqu'il s'agit du stockage, qui plus est dans un environnement à ressources partagées ? Dans cette session, nous appliquerons les fondamentaux du stockage SQL Server pour la mise en place d'une infrastructure de stockage performante.

### 10h15 &#10148; Les groupes de disponibilité AlwaysOn par la pratique {#session02}

[Christophe Laporte, ConseilIT](https://www.linkedin.com/in/christophelaporte/)

Installer et configurer SQL Server est relativement simple, à fortiori si vous procédez via des scripts.
Ajouter une fonctionnalité de haute disponibilité l'est tout autant.
Après avoir abordé les principes théoriques du cluster et des groupes de disponibilités, nous utiliserons des scripts PowerShell afin d'effectuer une mise en œuvre automatisée.
Finalement, nous aborderons les problématiques de sauvegarde, d'implémentation dans un environnement Cloud, etc …

### 11h30 &#10148; Je veux migrer mes bases dans Azure MAIS … {#session03}

[Julien Pierre, Microsoft](https://www.linkedin.com/in/julien-pierre-15782127/) et [Sylvain Pagès](https://www.linkedin.com/in/sylvain-pag%C3%A8s-2b5170107/)

Vous êtes nombreux à vous poser des questions sur comment maîtriser la migration de vos bases dans Azure.  
Sylvain et Julien partageront leur expérience et leurs retours terrain sur les nombreux projets de migration de bases SQL Server vers Azure SQL.  
Quels sont les différents chemins de migrations OnPrem vers Azure ?  
Quels sont les pièges et comment les éviter ?  
Quelles sont les recommandations à suivre ?

### 13h30 &#10148; Gérer les bases de données à forte volumétrie {#session04}

[Arian Papillon, Datafly, MVP](https://www.linkedin.com/in/arianpapillon/)

L'administration des bases de données devient plus délicate lorsqu’on gère de fortes volumétries.  
Dans cette session nous évoquerons les problématiques et les solutions propres aux bases de données volumineuses.

- Performances et Indexation
- Stockage et partitionnement
- Administration et sauvegardes
- Outils, trucs et astuces

### 14h45 &#10148; SQL Server sur Google Cloud Platform {#session05}

[Clément Hugé, Google](https://www.linkedin.com/in/clementhuge/)

SQL Server est disponible en IaaS (*Infrastructure as a Service*) et PaaS (*Platform as a Service*) sur Google Cloud Plaform (GCP).  
Dans cette session, nous allons voir comment créer une instance, la gérer et s'y connecter.  
Nous aborderons également les diférentes fonctionnalités, comme la haute disponibilité, les sauvegardes automatiques, le clonage, la supervision, et comment sécuriser les données au repos et en transit.

### 16h00 &#10148; Simplifier vos projets BI grâce à Azure Data Factory {#session06}

[Sébastien Kobenan, Exakis Nelite](https://www.linkedin.com/in/sebastien-kobenan/)

- Brève présentation du service Azure Data Factory
-	Architecture type d’un projet Data Factory
-	Présentation d’un cas d’utilisation de Data Factory :
    - Copie de fichiers d’Azure Data Lake Gen2 vers une base de données Azure SQL (avec brève présentation d’Azure Data Lake et Azure SQL)
    - Sécurisation des données dans Azure Virtual Network (seules des ressources Azure dans le VNet pourront accéder aux données soit dans le Data Lake ou soit dans Azure SQL)
    - Communication entre les différents services dans le VNet via des Private Endpoint : pour lire/écrire des données dans le Data Lake ou dans Azure SQL, Data Factory devra passer par des Private Endpoint. (Là aussi brève explication de ce qu’est un Private Endpoint)
    - Authentification via des Managed Identities : pour lire/écrire des données dans Azure Data Lake ou Azure SQL, Data Factory devra s’authentifier à travers des Managed Identities. (avec bien sûr une brève présentation de d’Azure Managed Identities)

### 17h15 &#10148; Query Store, bientôt incontournable ? {#session07}

[Steven NAUDET, DBI Services](https://www.linkedin.com/in/steven-naudet-aa540158/)

Steven a 10 ans d'expérience SQL Server, il est actuellement consutant chez dbi services, en Suisse.  
Le Query Store est une fonctionnalité disponible depuis SQL Server 2016 mais semble toujours assez peu utilisé.  
Les informations déjà connues autour de la version 2022 annoncent un Query Store omniprésent sur SQL Server.

Dans cette session nous verrons en introduction ce qu'est le Query Store. Puis nous ferons le tour des fonctionnalités récentes et à venir en lien avec Query Store comme l'Automatic Tuning ou les Query Store Hints.