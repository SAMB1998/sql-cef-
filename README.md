# Tifosi Database

## Description
Ce projet contient les scripts SQL nécessaires pour créer, insérer des données et sauvegarder la base de données `tifosi`.

## Contenu du Repository
- `create_database.sql` : Script pour créer la base de données `tifosi` et ses tables.
- `insert_data.sql` : Script pour insérer des données de test dans la base de données.
- `backup_tifosi.sql` : Script pour sauvegarder la base de données `tifosi`.

## Instructions

### Création de la Base de Données
1. Ouvrez MySQL Workbench.
2. Chargez et exécutez le script `create_database.sql`.

### Insertion des Données
1. Ouvrez MySQL Workbench.
2. Chargez et exécutez le script `insert_data.sql`.

### Sauvegarde de la Base de Données
1. Exécutez la commande suivante dans votre terminal :
   ```bash
   mysqldump -u root -p tifosi > C:\Users\bello\tifosi\backup_tifosi.sql
