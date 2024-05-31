+++
title = "DataFrogs 2023.01"
description = "Conférence DataFrogs 2024.01, le 1 juin 2024."
author = "Rudi Bruchez"
date = "2024-05-23"
tags = ["sqlserver"]
categories = ["conference", "sqlserver"]
[[images]]
  src = "img/2023/datafrogs03.png"
  alt = "Vous êtes démasqué"
  stretch = "vertical"
+++

**Inscrivez-vous sur [LinkedIn Events](https://www.linkedin.com/events/datafrogs2023-027094267767230513152/)**.

<!--more-->

## Samedi 1 juin 2024, en ligne

DataFrogs est une conférence communautaire gratuite sur Microsoft SQL Server.

Cette session aura lieu le samedi 1 juin 2024, en virtuel (Les liens pour les sessions Microsoft Teams seront disponibles quelques jours avant la conférence).

Inscrivez-vous sur [LinkedIn Events](https://www.linkedin.com/events/datafrogsjuin20247183857787653750784/) pour obtenir les informations pratiques.

Il y aura cette fois-ci cinq sessions, la conférence se tiendra du matin jusqu'en fin d'après-midi. La dernière session sera une session _Questions/Réponses_ où vous pourrez poser vos questions, partager vos expériences, etc. à micros ouverts. Profitez-en !

Les sessions seront disponibles pour tous, et les enregistrements seront ensuite posés sur [la chaîne YouTube de DataFrogs](https://www.youtube.com/@datafrogs).

## Programme

| Heure | Session | Qui | Lien |
| -------- | ------ | ------ | ------ |
| 09h00 | [Azure Arc SQL]({{< relref path="#arc" >}}) | [Julien Pierre, Microsoft](https://www.linkedin.com/in/julien-pierre-15782127/) et [Richard Prade, Microsoft](https://www.linkedin.com/in/richard-prade-81155b8/) | [Lien Teams](https://teams.microsoft.com/l/meetup-join/19%3ameeting_NjI2NGI0NmEtY2Y0OS00Y2M2LTgzZjItNzQ4YjIyM2YwMGFl%40thread.v2/0?context=%7b%22Tid%22%3a%225cfe5ed9-932d-40ec-b146-19381d59e099%22%2c%22Oid%22%3a%220793833d-4db6-4d53-ba71-46eacc73020a%22%7d) |
| 10h15 | [Les Dernières Nouveautés Azure SQL Database et On-Prem]({{< relref path="#nouveautes" >}}) | [Julien Pierre, Microsoft](https://www.linkedin.com/in/julien-pierre-15782127/) et [Richard Prade, Microsoft](https://www.linkedin.com/in/richard-prade-81155b8/) | [Lien Teams](https://teams.microsoft.com/l/meetup-join/19%3ameeting_NTM0YjgyMTktNzAyNi00Y2I2LTgxYzctZTI4Mjg4NTFkZjJi%40thread.v2/0?context=%7b%22Tid%22%3a%225cfe5ed9-932d-40ec-b146-19381d59e099%22%2c%22Oid%22%3a%220793833d-4db6-4d53-ba71-46eacc73020a%22%7d) |
| 11h30 | [Cas Client: amélioration des performances et de la maintenance des tables volumétriques et fortement sollicitées]({{< relref path="#CasClient" >}}) | [Clément Hugé](https://www.linkedin.com/in/clementhuge/) | [Lien Teams](https://teams.microsoft.com/l/meetup-join/19%3ameeting_Y2IyNjM1YWYtNmFlYy00YWViLWEwZjctODkyMDUwOTY4NmJk%40thread.v2/0?context=%7b%22Tid%22%3a%225cfe5ed9-932d-40ec-b146-19381d59e099%22%2c%22Oid%22%3a%220793833d-4db6-4d53-ba71-46eacc73020a%22%7d) |
| 13h30 | [Nettoyage des instances et bases de données SQL Server]({{< relref path="#nettoyage" >}}) | [Frédéric Brouard, SQL Spot](https://www.linkedin.com/in/frederic-brouard-alias-sqlpro-914761) et [Arian Papillon, Datafly, MVP](https://www.linkedin.com/in/arianpapillon/) | [Lien Teams](https://teams.microsoft.com/l/meetup-join/19%3ameeting_NmQzNTZiMWQtMWVkZS00NDVjLWExOTMtMTQwM2ExNjgwMGQ2%40thread.v2/0?context=%7b%22Tid%22%3a%225cfe5ed9-932d-40ec-b146-19381d59e099%22%2c%22Oid%22%3a%220793833d-4db6-4d53-ba71-46eacc73020a%22%7d) |
| 14h45 | [Migration de base de données SQL vers le cloud - Retour d'expérience]({{< relref path="#Cloud" >}}) | [David Barabarin, Migros Online](https://www.linkedin.com/in/mikedavem/) | [Lien Teams](https://teams.microsoft.com/l/meetup-join/19%3ameeting_YjY1MGQ3YWUtYjVlYS00ZDU2LThjNDYtZGUzOTViZGFiZGU1%40thread.v2/0?context=%7b%22Tid%22%3a%225cfe5ed9-932d-40ec-b146-19381d59e099%22%2c%22Oid%22%3a%220793833d-4db6-4d53-ba71-46eacc73020a%22%7d) |
| 16h00 | [Questions / Réponses aux experts SQL - session collective à micros ouverts]({{< relref path="#QA" >}}) | Micros ouverts | [Lien Teams](https://teams.microsoft.com/l/meetup-join/19%3ameeting_MGU0MDM1OTktZmExOC00NjQ0LTljYmQtNDkzYWY4YzVkMjk5%40thread.v2/0?context=%7b%22Tid%22%3a%225cfe5ed9-932d-40ec-b146-19381d59e099%22%2c%22Oid%22%3a%220793833d-4db6-4d53-ba71-46eacc73020a%22%7d) |

## Programme détaillé

### 09h00 &#10148; Azure Arc SQL {#arc}

[_Julien Pierre, Microsoft_](https://www.linkedin.com/in/julien-pierre-15782127/) et [_Richard Prade, Microsoft_](https://www.linkedin.com/in/richard-prade-81155b8/)

Azure Arc étend les services Azure aux instances SQL Server hébergées en dehors d’Azure.

Azure Arc vous permet donc de gérer toutes vos instances SQL Server à partir d'un point de contrôle unique : Azure. Julien et Richard vous présentent cette technologie et vous montrent comment l'utiliser pour gérer vos instances SQL Server.

### 10h15 &#10148; Les Dernières Nouveautés Azure SQL Database et On-Prem {#nouveautes}

[_Julien Pierre, Microsoft_](https://www.linkedin.com/in/julien-pierre-15782127/) et [_Richard Prade, Microsoft_](https://www.linkedin.com/in/richard-prade-81155b8/)

Les dernières nouveautés de SQL Server 2022 et Azure SQL Database. Toutes fraîches.

### 11h30 &#10148; Cas Client: amélioration des performances et de la maintenance des tables volumétriques et fortement sollicitées {#CasClient}

[_Clément Hugé_](https://www.linkedin.com/in/clementhuge/)

Comment résoudre des problèmes de maintenance et de performance avec le partitionnement de données, en étant sur l'édition standard de SQL server 2022 ? Clément présentera un cas concret chez un client chez Google Cloud qui a mis en place une architecture découplée pour intégrer les mesures et configurations des équipements sur le terrain vers une base de données centralisée MSSQL server sur la plateforme managée Google Cloud SQL.

Clément présentera l'architecture découplée, la méthodologie des tests de sollicitation et la mise en place de la nouvelle structure des tables.

### 13h30 &#10148; Nettoyage des instances et bases de données SQL Server {#nettoyage}

[_Frédéric Brouard, SQL Spot_](https://www.linkedin.com/in/frederic-brouard-alias-sqlpro-914761) et [_Arian Papillon, Datafly, MVP_](https://www.linkedin.com/in/arianpapillon/)

+ Combien de login avez vous qui ne servent plus à rien ?
+ Combien d'utilisateurs SQL sont orphelins dans mes bases ?
+ Méfions nous de l'impersonalisation... EXECUTE AS !
+ Combien de bases ne sont plus accédées ?
+ Combien de fichiers de données ou de groupes de fichiers sont vides ?
+ Combien de table ne sont plus accédés ?
+ Combien d'index ne sont plus utilisés ?
+ Combien d'index sont redondants ou inclus ?
+ Combien de statistiques sont redondantes ?

### 14h45 &#10148; Migration de base de données SQL vers le cloud - Retour d'expérience {#Cloud}

[_David Barabarin, Migros Online_](https://www.linkedin.com/in/mikedavem/)

Si vous envisagez de migrer votre plateforme de base de données SQL vers Azure, cette session suscitera certainement votre intérêt avec un retour d'expérience concret de migration dans le cadre d'une stratégie cloud first et d'un environnement orienté devops et microservices.

Bien que ce projet de migration ait été vaste, nous mettrons un accent particulier sur la partie plateforme de base de données incluant plusieurs chapitres tels que les objectifs business, la collaboration, la planification, les phases de conception de l'architecture cloud et défis techniques à relever pour réussir cette migration.

### 16h00 &#10148; Questions / Réponses aux experts SQL {#QA}

Session collective à micros ouverts

Question ? Anecdotes ? Retours d'expérience ? Venez discuter avec nous !

Si les experts ne savent pas, on demandera à ChatGPT.
