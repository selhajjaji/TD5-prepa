# TD5 – Java Spring Boot : Observabilité, Healthcheck, Logs JSON, SBOM & Release Candidate

Ce dépôt contient une application **Spring Boot** utilisée dans le cadre du **TD5 INF1763 – Techniques et outils professionnels de développement logiciel**.  
L’objectif est de préparer une **Release Candidate** en appliquant des pratiques modernes de **DevOps / DevSecOps** :

- Observabilité (Actuator, endpoint `/actuator/health`)
- Logs structurés JSON (Logback Encoder)
- Healthcheck Docker
- Génération d’une SBOM (Syft)
- Scan de vulnérabilités (Grype)
- Intégration Continue (GitHub Actions)
- Publication d’une Release Candidate sur GitHub

---

## 1. Prérequis

- **Java** : JDK 21 (Temurin recommandé)
- **Maven** : 3.9+
- **Docker** installé et en cours d’exécution
- **Git** installé
- (Optionnel pour la partie sécurité)
    - **Syft** pour la SBOM
    - **Grype** pour le scan de vulnérabilités

---

## 2. Démarrage local de l’application

### 2.1. Compilation

```bash
mvn clean package -DskipTests
