# 🚀 Smart Delivery - La Révolution de la Livraison Intelligente  

<div align="center">
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=spring&logoColor=white" alt="Spring Boot">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Keycloak-EC5425?logo=keycloak&logoColor=white" alt="Keycloak">
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Microservices-architecture-FF6C37?logo=kubernetes&logoColor=white" alt="Microservices">
</div>

## 🌟 L'Expérience de Livraison Réinventée

**Smart Delivery** révolutionne l'écosystème food-tech en connectant intelligemment :
- 👨‍🍳 **Restaurateurs** - Gestion simplifiée des commandes et stocks
- 🚴 **Livreurs** - Optimisation des tournées en temps réel
- 🛒 **Clients** - Commandes ultra-rapides et suivi précis

<div align="center">
  <img width="70%" src="https://via.placeholder.com/800x400/2D3748/FFFFFF?text=Smart+Delivery+Workflow" alt="Architecture Diagram">
</div>

## � Pourquoi Choisir Smart Delivery ?

| Fonctionnalité | Technologie | Bénéfice |
|---------------|------------|----------|
| 🍽️ Menu Digital | Spring Boot | Mise à jour en temps réel |
| 🗺️ Optimisation Tournées | Python/OSRM | Réduction de 30% des temps de livraison |
| 🔐 Auth Sécurisée | Keycloak | Protection des données RGPD |
| 📦 Gestion Stocks | Spring Data | Synchronisation fournisseurs automatique |
| 📱 Notifications Push | WebSockets | Updates en <500ms |

## 🛠️ Architecture Technique

```mermaid
graph TD
  A[Client] --> B[API Gateway]
  B --> C[Service Commande] et [service Fournisseur]
  B --> D[Service Notification]
  C --> E[(BD Commande)]
  D --> F[WebSockets]
  G[Python Scraper] --> H[Service Livreur]
  H --> I[OpenStreetMap]
