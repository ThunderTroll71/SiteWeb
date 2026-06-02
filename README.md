# PeerPlex

PeerPlex est une application web permettant à des utilisateurs connectés de créer ou rejoindre une session grâce à un code.

Le projet contient aussi un portfolio personnel intégré au site.  
Ce portfolio permet de présenter un profil, des compétences, des expériences professionnelles ainsi que des projets réalisés.

Le projet utilise un système d’authentification, une base de données SQLite, un espace administrateur et une communication temps réel avec Socket.IO / WebRTC.

## Fonctionnalités

- Connexion avec compte utilisateur
- Authentification sécurisée avec JWT
- Mots de passe chiffrés avec bcrypt
- Création de sessions avec code unique
- Possibilité de rejoindre une session existante
- Communication temps réel avec Socket.IO
- Signalisation WebRTC pour connecter deux utilisateurs
- Interface administrateur
- Gestion des utilisateurs
- Statistiques administrateur
- Historique des sessions
- Portfolio personnel intégré dans la page /Portfolio
- Présentation du profil
- Présentation des compétences
- Présentation des expériences professionnelles
- Présentation des projets réalisés

## Technologies utilisées

- HTML
- CSS
- JavaScript
- Node.js
- Express
- Socket.IO
- SQLite avec better-sqlite3
- JWT
- bcryptjs

## Structure du projet

```text
SiteWeb/
├── index.html          # Page de connexion
├── app.html            # Interface principale de l'application
├── admin.html          # Interface administrateur
├── portfolio.html      # Page du portfolio personnel, si présente
├── style.css           # Feuille de style
├── app.js              # Logique côté client
├── server.js           # Serveur Node.js / Express
├── seed-admin.js       # Script de création du compte administrateur
├── package.json        # Dépendances et scripts npm
├── CNAME               # Configuration du nom de domaine
└── README.md