# siem-elk-project

SIEM ELK Project
Présentation

Ce projet consiste à mettre en place une solution de SIEM (Security Information and Event Management) basée sur la stack ELK (Elasticsearch, Logstash, Kibana).
L’objectif est de centraliser, analyser et visualiser les logs provenant de différentes sources afin de détecter des activités suspectes et renforcer la sécurité du système d’information.

La solution repose sur l’utilisation de Filebeat pour la collecte des logs, Logstash pour leur traitement, Elasticsearch pour le stockage et Kibana pour la visualisation.
Ce projet permet ainsi de simuler un environnement réel de supervision de sécurité et de mettre en œuvre des cas d’usage tels que la détection d’attaques par force brute ou l’analyse des événements système.
################################################################################################################################################

1-Filebeat collecte les logs depuis tes sources (serveurs, applis, réseau) et les envoie via le protocole Beats

2-Logstash les reçoit, les parse et les transforme selon ton logstash.conf
3-Elasticsearch stocke et indexe tout pour la recherche
4-Kibana offre la visualisation, les dashboards et l'interface SIEM
