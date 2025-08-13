# Backend Learning Journey 🚀
_Projet fil rouge pour apprendre, pratiquer et partager mes compétences backend._

## 📌 Objectif
Ce repository documente mon parcours d'apprentissage backend sur 12 semaines.  
Chaque semaine, j’apprends ou révise un sujet clé, je l’applique à un projet concret, puis je partage mes avancées sur LinkedIn.

**Projet fil rouge :** API de gestion de tâches avec authentification, sécurité, performance et observabilité.  
**Stack principale :** Symfony 7, MySQL, Redis, Kafka, Docker, PHPUnit, Swagger/OpenAPI

---

## 📅 Plan d'apprentissage

| Semaine | Sujet principal | Dossier |
|---------|----------------|---------|
| 1 | Bases backend & setup | `01-basics` |
| 2 | API Design | `02-api-design` |
| 3 | Sécurité - Niveau 1 | `03-security-1` |
| 4 | Sécurité - Niveau 2 | `04-security-2` |
| 5 | Database Engineering | `05-database` |
| 6 | Performance Optimization | `06-performance` |
| 7 | Architecture | `07-architecture` |
| 8 | DevOps Awareness | `08-devops` |
| 9 | Distributed Systems | `09-distributed` |
| 10 | Observabilité | `10-observability` |
| 11 | Tests | `11-tests` |
| 12 | Finalisation | `12-final` |

---

## 🛠️ Stack & Outils

- **Langage :** PHP 8.3
- **Framework :** Symfony 7
- **Base de données :** MySQL 8
- **Cache :** Redis
- **Containerisation :** Docker + docker-compose
- **Tests :** PHPUnit
- **Documentation API :** Swagger (NelmioApiDocBundle)
- **Monitoring :** Grafana / Prometheus
- **Message broker :** Kafka

---

## 📂 Structure

Chaque dossier contient :
- Code source Symfony
- Documentation spécifique à la semaine
- Exemples d’utilisation

---

## 🚀 Démarrage

```bash
# Cloner le repository
git clone https://github.com/belgacemkh/backend-learning-journey.git
cd backend-learning-journey

# Installer les dépendances Symfony
composer install

# Lancer avec Docker
docker-compose up -d
