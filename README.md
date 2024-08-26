Dans ce projet BI, nous avons travaillé sur une base de données appelée "ovh", destinée à la gestion des tickets. Après avoir mené différentes analyses en groupe, nous avons conçu un schéma en étoile, qui nous a permis de créer un entrepôt de données (data warehouse). En utilisant Talend, nous avons développé plusieurs jobs pour extraire les données nécessaires de la base de
données source "ovh" et les transférer dans notre entrepôt de données "dwh_ovh", incluant la table des faits et les dimensions. Une fois l'entrepôt de données constitué, nous avons utilisé Power BI pour générer des rapports tels que:
    - le nombre de tickets par type de client,
    - le nombre de tickets par année,
    - le nombre de tickets par type d'incident et serveur,
    - le nombre de tickets créés les lundis.
