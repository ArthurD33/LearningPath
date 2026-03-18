# Networking Basics - Documentation Synthétique

Ce dépôt regroupe les concepts fondamentaux de la communication réseau, de l'infrastructure physique aux modèles de référence, basés sur les standards de l'industrie.

---

## 1. Types de Réseaux et Données
*Résumé : Définition de l'internet comme un réseau de réseaux et classification des données personnelles.*

* **Internet** : Une collection mondiale de réseaux interconnectés (internetwork) coopérant pour échanger des informations via des standards communs.
* **Types de réseaux** :
    * **Small Home** : Connecte quelques appareils à domicile.
    * **SOHO (Small Office/Home Office)** : Permet aux bureaux distants de se connecter à un réseau d'entreprise ou d'accéder à des ressources centralisées.
    * **Medium/Large** : Réseaux d'entreprises ou d'écoles avec des centaines ou milliers d'hôtes.
* **Données personnelles** : Classées en données volontaires (partagées explicitement), observées (actions enregistrées comme la localisation) et inférées (basées sur l'analyse, comme un score de crédit).

## 2. Indicateurs de Performance
*Résumé : Mesure de la capacité théorique (bande passante) par rapport à la performance réelle (débit).*

* **Bande passante (Bandwidth)** : Capacité théorique d'un support à transporter des données, mesurée en bits par seconde (Kbps, Mbps, Gbps).
* **Throughput (Débit)** : Quantité réelle de données transférées, influencée par le trafic et la latence.
* **Latence** : Temps nécessaire, incluant les délais, pour que la donnée voyage d'un point à un autre.

## 3. Composants de l'Infrastructure
*Résumé : Les trois piliers matériels supportant la plateforme réseau.*

* **End Devices (Hôtes)** : Interface entre l'humain et le réseau (ordinateurs, serveurs, imprimantes, caméras, smartphones).
* **Dispositifs intermédiaires** : Matériels qui dirigent le flux d'informations (switches, routeurs, points d'accès sans fil).
* **Supports (Media)** : Canaux physiques ou sans fil (câblage cuivre, fibre optique ou ondes).

## 4. Protocoles et Modèles de Référence
*Résumé : Cadres structurant les fonctions de communication en couches indépendantes.*

* **Modèle TCP/IP** : Structure en 4 couches (Application, Transport, Internet, Network Access) pour les communications internet.
* **Modèle OSI** : Modèle de référence à 7 couches (Physique, Liaison de données, Réseau, Transport, Session, Présentation, Application) utilisé pour le design et le dépannage.
* **Encapsulation** : Processus consistant à placer un format de message à l'intérieur d'un autre (avec un en-tête d'adressage) pour permettre sa livraison.

## 5. Supports de Transmission (Media)
*Résumé : Caractéristiques des différents médias physiques et sans fil.*

* **Câbles en métal (Cuivre)** : Données encodées en impulsions électriques (ex: Twisted-pair, Coaxial).
* **Fibre Optique** : Données encodées en impulsions lumineuses ; insensible aux interférences électriques et idéale pour les longues distances.
* **Sans fil** : Utilise des ondes électromagnétiques (Wi-Fi 802.11, Bluetooth, NFC).

## 6. La Couche d'Accès et Ethernet
*Résumé : Gestion de l'accès local au réseau via les commutateurs et l'adressage MAC.*

* **Ethernet** : Protocole dominant définissant le format des trames, leur taille et l'encodage.
* **Switch (Commutateur)** : Dispositif de couche 2 qui lit les adresses MAC pour créer des circuits temporaires, éliminant les collisions contrairement aux hubs obsolètes.
* **Table d'adresses MAC** : Base de données mise à jour dynamiquement par le switch pour associer chaque adresse MAC à un port physique.