<h1 align="center">📞 Application Client-Serveur de Carnet de Contacts avec Sockets en C 📞</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Language-C-blue" alt="Language">
  <img src="https://img.shields.io/badge/Status-En%20Cours-brightgreen" alt="Status">
  <img src="https://img.shields.io/github/license/votre-nom/projet-socket-carnet-contacts" alt="License">
</p>

<p align="center">Ce projet, développé et maintenu par Mohamed Amine Ait Jaakike, implémente une application client-serveur en C utilisant des sockets pour la gestion d'un carnet de contacts. Les fonctionnalités incluent l'authentification des utilisateurs, la gestion des contacts et des profils d'utilisateur administrateur et standard.</p>

## Fonctionnalités :

### Serveur :

- Authentification des utilisateurs à partir d'un fichier texte (`compte.txt`).
- Gestion des contacts à partir d'un fichier texte (`Contact.txt`).
- Support des profils d'utilisateur administrateur et standard.

### Client :

- Interface de saisie pour l'ajout, la recherche, la suppression et la modification des contacts (administrateur).
- Interface de saisie pour la recherche et l'affichage de tous les contacts (utilisateur standard).

## 📁 Fichiers inclus :

- `server.c` : Code source du serveur.
- `client.c` : Code source du client.
- `compte.txt` : Fichier contenant les informations d'authentification.
- `Contact.txt` : Fichier contenant les contacts.

## 📄 Structure des fichiers :

### server.c :

Le serveur gère les connexions client et offre les fonctionnalités suivantes :

- Authentification.
- Gestion des contacts (ajout, recherche, suppression, modification, affichage de tous les contacts).

### client.c :

Le client permet aux utilisateurs de se connecter au serveur et d'effectuer les opérations correspondantes à leur profil :

- Administrateur : gestion complète des contacts.
- Utilisateur standard : recherche et affichage des contacts.

## 🛠️ Instructions de Compilation et d'Exécution :

### Compilation :

Pour compiler les fichiers source, exécutez les commandes suivantes :
## Auteur :

Ce projet est développé et maintenu par **Mohamed Amine Ait Jaakike**.

```bash
gcc -o server server.c -lpthread
gcc -o client client.c
