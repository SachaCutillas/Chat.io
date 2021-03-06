# Chat.io
Projet pour le cours IA et Système Embarqué

## Bienvenue sur Chat.io

Chat.io est un chatroom fonctionnant sans connexion internet. Le but est de pouvoir développer une application permettant aux personnes habitant dans des zones sans accés internet de communiquer entre elles. C'est une application qui permet aussi de contrôler de manière très simple des objets connectés en local via le réseau WiFi de la carte.
Il suffit alors de créer un réseau de carte ESP32 communiquant sur la même adresse IP.

Vous pouvez également contrôler l’allumage de la led. Pour cela taper « /help » dans le chat pour obtenir la commande.

Pour commencer, se connecter au point d’accès Chat.io en WiFi.
Ouvrir ensuite l’application Android dédiée et appuyer sur « Démarrer le Chat ».

## Liste des commandes

* /led ON : allumer la led de l'ESP32
* /led OFF : éteindre la led de l'ESP32
* /help : liste des commandes disponibles dans le chat
* c : commande à écrire dans le moniteur série de la carte pour supprimer tous les messages

## Fichiers

Le code à téléverser sur l'ESP32 se trouve dans le dossier chatio. Le code complet pour l'application Android est dans le fichier .zip mais l'application peut être testée en utilisant le fichier apk via un émulateur Android.

## Compatibilité

L'application est optimisé pour l'affichage sur un téléphone en mode portrait.
