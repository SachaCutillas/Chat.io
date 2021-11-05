# Chat.io
Projet pour le cours IA et Système Embarqué

## Bienvenue sur Chat.io

Chat.io est un chatroom fonctionnant sans connexion internet. Le but est de pouvoir développer une application permettant aux personnes habitants dans des zones sans accés internet de communiquer entre elles.
Il suffit alors de créer un réseau de carte ESP32 communiquant sur la même adresse IP.

Vous pouvez également contrôler l’allumage de la led. Pour cela taper « /help » dans le chat pour obtenir la commande.

Pour commencer, connectez vous au point d’accès Chat.io en WiFi.
Ouvrez ensuite l’application Android dédiée et appuyez sur « Démarrer le Chat ».

## Liste des commandes

* /led ON : allumer la led de l'ESP32
* /led OFF : éteindre la led de l'ESP32
* c : commande à écrire dans le moniteur série de la carte pour supprimer tous les messages

## Fichiers

Le code à téléverser sur l'ESP32 se trouve dans le dossier chatio. Le code complet pour l'application Android est dans le fichier .zip mais l'application peut être tester en utilisant le fichier apk via un émulateur Android.
