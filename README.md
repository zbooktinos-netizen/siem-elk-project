# siem-elk-project

#  SIEM ELK Project

##  Présentation

Ce projet a pour objectif de concevoir et déployer une solution de **SIEM (Security Information and Event Management)** basée sur la stack ELK : **Elasticsearch, Logstash et Kibana**.

L’objectif principal est de centraliser, analyser et visualiser les logs issus de différentes sources (systèmes, applications, réseau) afin de détecter des comportements suspects et renforcer la sécurité du système d’information.

Cette solution permet de reproduire un environnement réel de supervision de sécurité, en mettant en œuvre des mécanismes de collecte, de traitement et de corrélation des événements.

---

##  Architecture de la solution

L’architecture repose sur plusieurs composants interconnectés :

* **Filebeat** : agent léger chargé de collecter les logs depuis les différentes sources (serveurs, applications, équipements réseau) et de les transmettre.
* **Logstash** : outil de traitement des logs qui reçoit les données, les analyse (parsing), les enrichit et les transforme selon les règles définies dans le fichier `logstash.conf`.
* **Elasticsearch** : moteur de stockage et d’indexation permettant de stocker les logs et d’effectuer des recherches rapides et efficaces.
* **Kibana** : interface graphique permettant la visualisation des données, la création de dashboards et l’analyse des événements de sécurité.

---

##  Fonctionnement global

1. **Collecte des logs** : Filebeat récupère les logs depuis les machines sources et les envoie via le protocole Beats.
2. **Traitement des données** : Logstash reçoit les logs, les parse et applique des transformations.
3. **Stockage et indexation** : Elasticsearch stocke les données et les rend accessibles pour la recherche.
4. **Visualisation et analyse** : Kibana permet d’explorer les logs, de créer des tableaux de bord et de détecter des incidents.

---

##  Cas d’usage

Ce SIEM permet notamment de :

* Détecter des attaques par **force brute (SSH, login)**
* Surveiller les événements système
* Analyser les logs en temps réel
* Identifier des comportements anormaux

---

##  Objectif pédagogique

Ce projet s’inscrit dans une démarche d’apprentissage et de mise en pratique des concepts de **cybersécurité opérationnelle**, notamment :

* la centralisation des logs
* la détection d’incidents
* la supervision de la sécurité

---

##  Auteur


lawson
