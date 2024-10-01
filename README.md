# XShot : Gestion et Recherche de Photos d'Événements Sportifs

Les marathons et autres événements sportifs attirent chaque année des milliers de participants et de spectateurs. Capturer et immortaliser ces moments devient une tâche essentielle pour les organisateurs et les participants. Cependant, trier et retrouver les photos spécifiques parmi des centaines, voire des milliers de clichés peut se révéler une tâche titanesque et chronophage. C’est dans ce contexte que notre projet, XShot, s’inscrit.

XShot est un site web innovant, intégrant un modèle d’intelligence artificielle (IA), conçu pour faciliter la gestion et la recherche de photos prises lors de marathons et d’événements similaires. Notre plateforme permet aux participants de retrouver facilement leurs photos en utilisant leur numéro de dossard, grâce à une technologie avancée de reconnaissance de caractères.

## Technologies Utilisées

### Frontend
Pour le développement du frontend, nous avons utilisé [React](https://reactjs.org/), une bibliothèque JavaScript populaire pour construire des interfaces utilisateur interactives et dynamiques. React permet de créer des composants réutilisables et facilite la gestion de l’état de l’application, offrant une expérience utilisateur fluide et réactive.

### Backend
Le backend de notre application est construit avec [Flask](https://flask.palletsprojects.com/), un micro-framework en Python. Flask est léger et flexible, ce qui le rend idéal pour développer des applications web robustes et performantes. Il permet de gérer les requêtes HTTP, l’authentification des utilisateurs, et l’interaction avec les bases de données.

### Intelligence Artificielle
Pour la détection et la reconnaissance des numéros de dossard dans les photos, nous avons intégré les technologies suivantes :

- **YOLO (You Only Look Once)** : Un modèle de détection d’objets en temps réel, utilisé pour identifier les zones des images contenant des numéros de dossard.
- **EasyOCR** : Une bibliothèque OCR (Reconnaissance Optique de Caractères) simple à utiliser, permettant de lire les numéros de dossard détectés par YOLO.

Ces technologies combinées assurent une reconnaissance précise et rapide des numéros de dossard dans les photos, permettant ainsi aux utilisateurs de trouver facilement leurs images.

## Accès aux Répertoires GitHub

- **Frontend** : Retrouvez le code source du frontend sur GitHub via le lien suivant : [front-end_XShot](https://github.com/anassBERRABEH/Front_XShoot)
- **Backend** : Retrouvez le code source du backend sur GitHub via le lien suivant : [back-end_XShot](https://github.com/anassBERRABEH/Back_XShoot)
