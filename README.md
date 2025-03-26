# Atelier 5 : Programmation Asynchrone
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![Laravel](https://img.shields.io/badge/Laravel-8.x-red)
![WebSockets](https://img.shields.io/badge/WebSockets-Pusher-blueviolet)
![Highcharts](https://img.shields.io/badge/Visualisation-Highcharts-green)
## 📌 Objectif
Se familiariser avec les concepts de programmation asynchrone en JavaScript et leur intégration avec une API Laravel, incluant :
- Promises et async/await
- Gestion de fichiers
- Opérations CRUD
- Communication en temps réel avec WebSockets

---
### 🛠️ Exercice 1 : Données utilisateur asynchrones
**Tâches :**
- Créer une fonction asynchrone simulant la récupération de données utilisateur.
- Afficher un profil utilisateur dynamique.
- Ajout de nouvelles données (login, mot de passe, adresse, etc.) et affichage sous forme de tableau.
- Chaîner des Promises pour des séquences asynchrones.

### 📂 Exercice 2 : Gestion de fichiers
**Tâches :**
- Création d'une route et d'un contrôleur pour le téléchargement de fichiers.
- Utilisation de fetch pour envoyer une requête POST à l'API Laravel. 
- Récupération des fichiers avec une requête GET et affichage dynamique. 
- Gestion des Promises pour assurer l'affichage des données.

### 🏫 Exercice 3 : CRUD Salles
**Tâches :**
- Créer une migration rooms (id, name, capacity).
- Développer un CRUD complet avec interface.
- Gérer les réponses asynchrones.

### 📈 Exercice 4 : Stocks temps réel

** ⚠️ L'implémentation des WebSockets (Exercice 4) n'a pas été réalisée** en raison d'une incompatibilité technique avec PHP 8.
 **Étapes prévues :**
- Configuration de Laravel WebSockets et Pusher. 
- Création de la migration stocks {id, product_name, quantity}. 
- Implémentation des méthodes CRUD dans StockController avec émission d'événements StockUpdated. 
- Intégration de Highcharts pour la visualisation de l'évolution des stocks en temps réel.

