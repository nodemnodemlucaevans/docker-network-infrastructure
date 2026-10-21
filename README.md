#  Infrastructure Réseau Conteneurisée (Docker & Network Isolation)

**Auteur :** Nodem Nodem Luca Evans  
**Spécialité :** Génie Software, Réseaux & Infrastructure — Keyce Informatique et IA

---

##  Description du Projet
Ce laboratoire présente le déploiement, la segmentation réseau et la sécurisation d'une infrastructure applicative multi-conteneurs utilisant **Docker** et **Docker Compose**.

##  Stack Technique
- **Conteneurisation :** Docker / Docker Compose
- **Système d'Exploitation :** Linux Ubuntu
- **Services :** Nginx (Reverse Proxy), Web Services, Database

## Architecture Réseau
- Isolation du trafic via un réseau virtuel **Bridge Network Docker** dédié.
- Redirection de ports et restriction du trafic entrant/sortant.
- Persistance et sécurité des données via des **Volumes Docker**.

##  Lancement du Lab
```bash
# Cloner le dépôt
git clone [https://github.com/nodemnodemlucaevans/docker-network-infrastructure.git](https://github.com/nodemnodemlucaevans/docker-network-infrastructure.git)

# Démarrer les services
docker-compose up -d

