# 🏠 HomeLab & Infrastructure Cloud Privée

Ce dépôt documente l'architecture, la configuration et le déploiement de mon infrastructure d'auto-hébergement (HomeLab). Ce projet vise à maintenir un cloud privé souverain, sécurisé et automatisé, tout en servant d'environnement d'expérimentation pour mes charges de travail en Data Science et en IA.

---

## ⚙️ Architecture & Stack Technique

L'infrastructure est hébergée *on-premise* sur une machine reconditionnée optimisée pour la consommation énergétique, offrant un espace de stockage redondant et une base de calcul locale. Elle est gérée via **TrueNAS Scale**, un système d'exploitation basé sur Linux intégrant la conteneurisation.

* **OS / Hyperviseur :** TrueNAS Scale
* **Reverse Proxy & Ingress :** Nginx Proxy Manager (Routage, gestion centralisée et automatisation des certificats SSL).
* **Réseau & DNS :** AdGuard Home (Filtrage DNS et sécurisation du réseau local).

---

## 📦 Services Déployés (Conteneurs)

### 🧠 Intelligence Artificielle (Self-Hosted)
* **Ollama & Open-WebUI :** Exécution et interaction locale avec des modèles de langage (LLM) sur mon propre matériel, garantissant une souveraineté et une confidentialité totales des données.

### ☁️ Cloud & Gestion de Données
* **Nextcloud :** Hébergement de fichiers sécurisé, synchronisation et cloud privé.
* **Immich :** Photothèque intelligente et solution de sauvegarde automatisée haute performance.

### 🍿 Flux Multimédia & Automatisation
* **Jellyfin :** Serveur de streaming multimédia open-source.
* **Écosystème Arr & Téléchargement :** Pipeline automatisé et interconnecté pour la gestion, l'acquisition et l'organisation des flux (Sonarr, Radarr, Readarr, Bazarr, Prowlarr, qBittorrent, Flaresolverr).

---
