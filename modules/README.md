# Dossier `modules`

Ce dossier accueille les modules fonctionnels d’AtGroup. Chaque module est une unité indépendante qui ajoute des fonctionnalités spécifiques à la plateforme.

## Structure d’un module

Un module doit contenir :

- Un fichier `manifest.json` décrivant le module (nom, version, dépendances, etc.)
- Un dossier `src/` avec le code source
- Un dossier `assets/` pour les ressources (images, styles, etc.)
- Un fichier `README.md` propre au module

## Convention

Les modules doivent respecter l’API exposée par le cœur (`core/`) et ne pas modifier directement son comportement.
