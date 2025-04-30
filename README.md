# 🍽️ FlavorShare - Plateforme de Partage de Recettes de Cuisine

**FlavorShare** est une application web collaborative développée avec Angular. Elle permet aux utilisateurs de consulter, commenter, noter et partager des recettes culinaires. Ce projet a été conçu pour renforcer les compétences en développement frontend moderne, notamment Angular, les appels API, le routing, la gestion des formulaires et l’organisation modulaire.


## 📌 Fonctionnalités

### Utilisateur non connecté :
- 🔍 Recherche de recettes par nom ou chef
- 🧾 Consultation des recettes : nom, ingrédients, étapes, photo, catégorie
- 🧩 Filtrage par catégorie (végétarien, dessert, etc.) ou ingrédient principal
- ⭐ Notation des recettes (1 à 5 étoiles)
- 💬 Lecture des commentaires

### Utilisateur connecté :
- 🔐 Authentification via formulaire de login
- 📝 Ajouter des commentaires
- 🧑‍🍳 Proposer ses propres recettes _(option bonus)_

---

## 🧱 Structure des Composants Angular

- `navbar` : Barre de navigation + barre de recherche
- `home` : Page d’accueil avec recettes populaires
- `recipe-list` : Liste filtrable des recettes
- `recipe-detail` : Détail complet d’une recette + système de notes/commentaires
- `login` : Authentification de l’utilisateur
- `rating-system` : Système de notation (étoiles) et gestion des commentaires

---

## 🔧 Services Angular

- `RecipeService` : Gestion des recettes (GET, POST, etc.)
- `RatingService` : Gestion des notes et des commentaires
- `AuthService` : Authentification et gestion de session utilisateur

---

## 🧪 Technologies utilisées

| Outil / Tech | Description |
|--------------|-------------|
| **Angular 16+** | Framework frontend |
| **TypeScript** | Langage principal |
| **HTML/CSS** | Structure et style |
| **Tailwind CSS** ou **Bootstrap** | UI responsive |
| **JSON Server / Firebase** | Backend mock / authentification |
| **LocalStorage** | Gestion de session locale |
| **Git/GitHub** | Suivi de version |
| **Postman** | Test des appels API |
| **Figma / Adobe XD** | Maquettage |

---

## 🎯 Objectifs pédagogiques

- Maîtrise d'Angular (composants, services, routing, binding…)
- Mise en place d’un système de notation/commentaires
- Création d’une UI responsive et agréable
- Intégration d’une API JSON
- Implémentation de l'authentification
- Documentation et présentation professionnelle

---

## 📁 Lancement du projet

```bash
# Cloner le projet
git clone https://github.com/votre-utilisateur/flavorshare.git
cd flavorshare

# Installer les dépendances
npm install

# Lancer le serveur de développement
ng serve
