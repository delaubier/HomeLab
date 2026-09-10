## ⚙️ Architecture & Stack Technique

L'ensemble de l'infrastructure est déployé et géré via **TrueNAS Scale**, un système d'exploitation NAS basé sur Linux (Debian) intégrant nativement la conteneurisation et l'orchestration (Kubernetes/Docker).

* **OS / Hyperviseur :** TrueNAS Scale
* **Reverse Proxy & Ingress :** Nginx Proxy Manager (Routage et gestion centralisée des certificats SSL).
* **Réseau & DNS :** AdGuard Home (Filtrage DNS et blocage des requêtes malveillantes au niveau réseau).

---

## 📦 Services Déployés (Conteneurs)

### 🧠 Intelligence Artificielle (Self-Hosted)
* **Ollama & Open-WebUI :** Déploiement et exécution de modèles de langage (LLM) locaux sur mon propre matériel, garantissant une souveraineté totale des données pour mes projets d'IA.

### ☁️ Cloud & Gestion de Données
* **Nextcloud :** Hébergement de fichiers sécurisé, synchronisation et cloud privé.
* **Immich :** Photothèque intelligente (alternative auto-hébergée haute performance).

### 🍿 Flux Multimédia & Automatisation
* **Jellyfin :** Serveur de streaming multimédia open-source.
* **Écosystème Arr & Téléchargement :** Pipeline automatisé et interconnecté pour la gestion, l'acquisition et l'organisation des bibliothèques (Sonarr, Radarr, Readarr, Bazarr, Prowlarr, qBittorrent, Flaresolverr).
