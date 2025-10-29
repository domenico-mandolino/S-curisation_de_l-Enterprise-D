# S-curisation_de_l-Enterprise-D
Sécurisation de l'Enterprise-D
L'USS Enterprise a détecté des activités anormales dans ses systèmes

Objectifs de la Mission

En tant que membre de l'équipage, votre mission est de surveiller ces
activités, automatiser les alertes pour des réponses rapides, analyser les
menaces et réagir efficacement pour protéger le vaisseau et son équipage.
Vous devez :
Configurer les systèmes de monitoring de l'Enterprise-D.
- Automatiser les alertes pour une détection rapide des anomalies.
- Réaliser une analyse technique des menaces détectées.
- Élaborer et mettre en œuvre un plan de réponse aux incidents.
Chaque membre d'équipage aura accès à un environnement virtualisé pour
installer les outils :
- Outils de monitoring : Zabbix, Prometheus, Grafana.
- Automatisation des alertes : Nagios, ELK Stack.
- Analyse technique : Wireshark, Kibana.
- Réponse à incident : Playbooks de sécurité, TheHive, MISP (Malware
Information Sharing Platform).


Mission 01

Installation et configuration de Zabbix.
Ajouter des systèmes du vaisseau (CPU, RAM, Disque) à surveiller.
Visualiser les données collectées et créer des graphiques.

Mission 02

Installation de Prometheus.
Ajouter des jobs de scrape pour les systèmes du vaisseau.

Mission 03

Installation de Grafana.
Intégration Prometheus-Grafana : Créer des tableaux de bord pour visualiser
les données collectées par Prometheus.

Mission 04

Configuration des alertes dans Zabbix
Définir des triggers : Configuration de seuils pour des alertes sur utilisation
CPU, RAM, etc.
Créer des actions d'alerte : Configurer des notifications par subespace email
en cas de dépassement de seuil.


Mission 05

Installation de l'ELK Stack.
Configuration de Logstash : Configurer l'import de logs des systèmes du
vaisseau.
Création de visualisations dans Kibana : Configurer les dashboards pour
visualiser les logs.
Mise en place de Watcher dans Elasticsearch : Créer des alertes basées sur
des conditions spécifiques dans les logs.

Mission 06

Avec Wireshark
Configurer et démarrer une capture de paquets sur une interface réseau.
Identifier des paquets suspects, analyser des conversations subespace
TCP/IP.

Mission 07

Analyse de logs avec Kibana
Rechercher des événements spécifiques : Utiliser les capacités de recherche
de Kibana pour identifier des événements suspects.
Visualisation des tendances : Utiliser les graphiques pour analyser les
tendances des logs sur une période de temps


Mission 08

Réponse à incident, Création de Playbooks de sécurité
Définir des scénarios d'incidents : Par exemple, une intrusion des Borgs, une
tentative de sabotage des Klingons, etc.
Élaborer des procédures de réponse : Actions à mener pour contenir,
éradiquer et récupérer après un incident.

Mission 09

Installation de TheHive et MISP
Création de cas dans TheHive : Documenter un incident et assigner des
tâches de réponse.
Intégration avec MISP : Partager des indicateurs de compromission (IoC) et
analyser des menaces partagées.

Compétences visées

➔ Administrer et sécuriser les infrastructures virtualisées
➔ Participer à la détection et au traitement des incidents de sécurité
➔ Participer à la mesure et à l'analyse du niveau de sécurité de
l'infrastructure
➔ Mettre en œuvre et optimiser la supervision des infrastructures


Rendu

Le projet est à rendre sur https://github.com/prenom-nom/Secuenterprise

L’évaluation se fera sous forme de présentation avec support à l’équipe
pédagogique.

Base de connaissances

➔ Zabbix
➔ Prometheus
➔ Grafana
➔ Eleasticsearch
➔ Logstash
➔ Kikana
➔ Watcher-Elasticsearch
➔ Wireshark
TheHive
➔ MISP
