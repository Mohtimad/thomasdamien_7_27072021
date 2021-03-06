![localhost_8080_](https://user-images.githubusercontent.com/71820021/134806208-fc6d96bd-2c52-4cab-8d3d-a13fcb185d68.png)

# Groupomania - Projet 07
Pour faire fonctionner le projet, vous devez installer :

- NodeJS 12.14 ou 14.0 
- @vue/cli@4.5.13
- mySQL

## Installation
1. Cloner le projet.
2. Dans le dossier backend/ : `cd backend/`
3. Configurer le "./config/db.config"
4. (optionnel) Importer la DB test `./config/Dumb.sql`
```- Utilisateur test:
- admin: `admin.email.fr` pass: `abcABC123*`
- user: `user@email.fr` pass: `abcABC123!`
```
5. Démarrer le serveur: `npm install` `node server`
6. Dans un nouveau terminal: `cd frontend/` `npm install` `npm run serve`
7. Rendez-vous sur http://localhost:8080/

## Contexte du projet
- Le projet consiste à construire un réseau social interne pour les employés de Groupomania. Le but de cet outil est de faciliter les interactions entre collègues. Le département RH de Groupomania a laissé libre cours à son imagination pour les fonctionnalités du réseau et a imaginé plusieurs briques pour favoriser les échanges entre collègues.

## Exigences
- la web app doit pouvoir se connecter et se déconnecter à l’application et que la session de l’utilisateur persiste pendant qu’il est connecté.
- la présentation des fonctionnalités doit être simple ;
- la création d’un compte doit être simple et possible depuis un téléphone mobile ;
- le profil doit contenir très peu d’informations pour que sa complétion soit rapide ;
- la suppression du compte doit être possible ;
- l’accès à un forum où les salariés publient des contenus multimédias doit être présent ;
- l’accès à un forum où les salariés publient des textes doit être présent ;
- les utilisateurs doivent pouvoir facilement repérer les dernières participations des employés ;
- le ou la chargé-e de communication Groupomania doit pouvoir modérer les interactions entre salariés;

## Technologies à utiliser
- Une base de données relationnelles qui se manipule avec le langage SQL pour le stockage de données.
- Utiliser un framework Front-End au choix, le projet doit être codé en Javascript, donc pas le framework Symfony.
 
## Points de vigilance
- L'API utilisée devra impérativement respecter des pratiques de code sécurisé et respecter les standards WCAG.
