
#Projet application de chat avec Socket.io

Hello Bird - Application de Chat en Temps Réel
Hello Bird est une application de messagerie en temps réel qui permet aux utilisateurs de se connecter, d'envoyer des messages privés et de discuter en ligne. L'application gère l'authentification des utilisateurs, l'envoi de messages, et affiche le statut de connexion des utilisateurs (en ligne / hors ligne) avec des indicateurs visuels.

Technologies Utilisées
L'application Hello Bird repose sur un ensemble de technologies modernes pour offrir une expérience utilisateur fluide et en temps réel :

Frontend :
HTML / CSS / JavaScript : Pour la structure, le style et l'interaction de l'interface utilisateur.
Socket.IO : Pour la communication en temps réel entre les utilisateurs (mise en place du chat).
Backend :
NestJS : Un framework backend Node.js pour gérer la logique serveur, les routes, et les WebSockets.
Prisma ORM : Utilisé pour interagir avec une base de données PostgreSQL.
PostgreSQL : Base de données relationnelle pour stocker les utilisateurs et les messages.
JWT (JSON Web Tokens) : Pour l'authentification sécurisée des utilisateurs.
Fonctionnalités Principales
Inscription et Connexion des Utilisateurs : Chaque utilisateur peut créer un compte et se connecter via un système sécurisé avec JWT.
Chat Privé en Temps Réel : Les utilisateurs peuvent envoyer des messages privés à d'autres utilisateurs en temps réel.
Indicateur de Statut : Un point vert/rouge indique si un utilisateur est en ligne ou hors ligne.
Indicateur de Saisie : Les utilisateurs peuvent voir lorsqu'une personne est en train de taper un message.
Déconnexion : Les utilisateurs peuvent se déconnecter de leur compte.



Récapitulatif des principales commandes


Installer les dépendances :
npm install



Migrer la base de données :
npx prisma migrate dev --name init


Démarrer le serveur en mode production :
npm run start


Démarrer le serveur en mode développement :
npm run start:dev



Lancer l'interface utilisateur avec http-server :
npx http-server ./public
