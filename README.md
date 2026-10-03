# Mohamed Lamine Sanoh

**Data Engineer junior | Cloud Azure · SQL · Python · dbt**

Je développe des projets de pipelines ETL/ELT, de qualité des données et de Data Warehouse avec SQL, Python et les services data de Microsoft Azure. Mon parcours en finance et en gestion des risques m'aide à relier les données aux indicateurs et aux besoins métier.

Je recherche une opportunité de **Data Engineer junior en France**. Ce portfolio présente mes projets personnels, leur code et les choix techniques que je mets en pratique.

## Cloud Azure : mes réalisations

| Service | Mise en pratique dans mes projets |
|---|---|
| **Azure Data Factory** | Ingestion depuis SQL Server et Azure SQL, copie de données vers le Data Lake, pipelines paramétrés et déclenchement de notebooks Databricks. |
| **Azure Data Lake Storage Gen2** | Organisation des données en couches Bronze, Silver et Gold, avec des fichiers Parquet et des tables Delta. |
| **Azure Databricks** | Nettoyage, normalisation et agrégation avec PySpark ; utilisation de tables Delta et de Unity Catalog dans le projet Medallion. |
| **Azure Synapse Analytics** | Création de vues et de procédures stockées SQL, puis orchestration de leur exécution dans un pipeline Synapse. |
| **Azure Key Vault** | Utilisation de secrets pour les accès au stockage, notamment via les secret scopes Databricks. |

## Projets à découvrir

| Projet | Ce qu'il présente | Technologies |
|---|---|---|
| [Pipeline data sur Azure](https://github.com/mlsanoh/azure-data-engineering-pipeline) | Ingestion SQL Server → Data Lake, transformations Bronze/Silver/Gold en PySpark et exposition des données avec Synapse. | ADF, ADLS Gen2, Databricks, PySpark, Synapse, Key Vault |
| [Architecture Medallion avec dbt et Azure](https://github.com/mlsanoh/Medallion-Architecture-DBT-Azure) | Ingestion paramétrée, snapshots pour l'historisation SCD Type 2, tables Delta et marts analytiques avec tests dbt. | ADF, ADLS Gen2, Databricks, Unity Catalog, dbt, Delta Lake |
| [Modern Data Stack](https://github.com/mlsanoh/Modern-Data-Stack-de-Production-Azure-Snowflake-dbt-Airflow-Docker) | Ingestion Azure Blob Storage → Snowflake, transformations dbt et modèle en étoile. Validation automatique sur GitHub ; exécution Snowflake manuelle. | Azure Blob Storage, Snowflake, dbt, Airflow, Docker, GitHub Actions |
| [Pipeline ETL de ventes](https://github.com/mlsanoh/Pipeline-ETL-Automated-Sales-Data-Quality-Orchestration-avec-Airflow-Docker-et-PostgreSQL) | Extraction CSV, nettoyage, détection des anomalies et chargement dans PostgreSQL, orchestrés en quatre tâches Airflow. | Python, Pandas, Airflow, Docker, PostgreSQL |
| [Data Warehouse e-commerce en SQL](https://github.com/mlsanoh/Projet-SQL-Marketplace-E-commerce) | Pipeline RAW → STAGING → DATA MART, contrôles qualité et analyses des ventes, des clients et des livraisons. | SQL, DuckDB, MotherDuck |

Autre projet : [classement LaLiga 2024–2025](https://github.com/mlsanoh/LaLiga-classement-2024-2025), avec extraction depuis une API, préparation des données en Python/Pandas et chargement dans MySQL.

## Autres compétences mises en pratique

- **SQL :** jointures, CTE, agrégations, fonctions de fenêtre, tables de faits et de dimensions.
- **Python :** Pandas pour la préparation des données ; PySpark pour les transformations dans Databricks.
- **dbt et Snowflake :** modèles en couches, historisation et tests de qualité des données.
- **Airflow, Docker, Git et GitHub Actions :** orchestration, environnement de développement et validation automatique du code.
- **Bases de données :** SQL Server, PostgreSQL, MySQL et DuckDB/MotherDuck.

## Contact

- [LinkedIn](https://linkedin.com/in/mlsanoh)
- [mlsanoh3@gmail.com](mailto:mlsanoh3@gmail.com)
- [Tous mes dépôts publics](https://github.com/mlsanoh?tab=repositories)
