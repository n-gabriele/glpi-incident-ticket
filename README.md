# 🎯 Projet : glpi-incident-ticket

Bienvenue dans **glpi-incident-ticket**, un projet que j’ai conçu pour **simplifier la gestion des incidents dans GLPI** via une interface automatisée.  
Ce projet a pour but de **faciliter la création, le suivi et la mise à jour des tickets d'incidents** dans l’environnement GLPI, que ce soit pour un technicien, un responsable IT ou un système externe.

---

## 🧩 Pourquoi ce projet ?

Dans un environnement où GLPI est utilisé comme outil de helpdesk, il devient vite fastidieux de :
- créer manuellement des tickets à la volée,
- suivre leur état en temps réel,
- les attribuer ou les clore efficacement.

J’ai donc développé ce module pour :
- **automatiser les tâches répétitives liées aux incidents**,
- **gagner du temps** pour les équipes techniques,
- **garantir un meilleur suivi** des interventions.

---

## 🚦 Objectifs pour l’utilisateur

Si tu utilises ce projet, tu pourras :
- Créer un ticket d’incident en ligne de commande en 5 secondes.
- Mettre à jour l’état d’un ticket automatiquement.
- Rechercher rapidement les tickets en cours ou clos.
- Lancer ces actions depuis un autre outil (ex : un script de supervision ou un bot).

---

## 🔧 Pré-requis

Avant de commencer, tu dois t’assurer d’avoir :
- un accès à une instance **GLPI avec l’API REST activée**,
- un **token d’utilisateur** et un **token d’application** GLPI,
- **Python 3.x** installé (si tu utilises la version Python),
- les dépendances installées via :
  ```bash
  pip install -r requirements.txt
