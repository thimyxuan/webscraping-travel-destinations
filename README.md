## Clone

```$ git clone https://github.com/thimyxuan/webscraping-travel-destinations.git```

## Dépendances

```$ pip install library_name```

Pour utiliser ce projet vous aurez besoin d'installer les librairies ci-dessous.

## Stack technique 

- Python
- Pandas
- Numpy
- Requests
- Scrapy
- Plotly
- Boto3
- Sqlalchemy
- Psycopg2

## Sujet

Kayak souhaite créer une application de recommandation de lieux où passer ses futures vacances.

Nous avons la mission de trouver le top 5 des destinations françaises avec la meilleure météo, et les 20 meilleurs hôtels à proximité.

## Problématique

Le but : 
- Utiliser des API et les techniques de webscraping pour récupérer les données qui nous intéressent
- Visualiser les meilleures destinations et les hôtels sur une carte
- Mettre les données à disposition dans un datalake et dans un datawarehouse

## Plan 

PARTIE 1 - Trouver les données météo
- API Nominatim : données gps
- API Openweather : prévisions météo
- Sélection des 5 meilleures destinations
- Visualisation du top 5 sur carte

PARTIE 2 - Trouver les meilleurs hôtels
- Webscraping du site booking.com
- Enregistrement fichier json

PARTIE 3 - Regroupement des données
- Nettoyage des données du webscraping
- Visualisation des hôtels sur carte

PARTIE 4 - Mise à disposition des données
- Enregistrement dans un S3 bucket (datalake)
- Création de la base de données PostGreSQL
- Enregistrement dans AWS RDS (datawarehouse)
- Test de requêtes SQL