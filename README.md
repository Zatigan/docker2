# Docker 2

## Objectif
L'objectif du présent travail est de réaliser le premier Dockerfile et .dockerignore pour appréhender le fonctionnement de Docker.

## Attendus
- [x] Créer le Dockerfile selon les consignes
- [x] Créer un .dockerignore adapté
- [x] Pouvoir créer une image du projet
- [x] Pouvoir lancer le conteneur dans un navigateur

## Exécuter le projet

1. Cloner le projet sur votre machine.
   
2. Vérifier que vous avez Docker d'installer sur votre machine : `
docker --version`.
Normalement, vous devez voir la version courante présente sur votre ordinateur.

3. Ouvrir un terminal à la racine du projet cloné.

4. Lancer les commandes suivantes
``` bash
# D'abord
docker build -t frontend-dockerfile .

# Puis
docker run --name frontend-test -p 4242:5173 frontend-dockerfile 
```

6. Ouvrir le navigateur de votre choix et se rendre sur 
`
http://localhost:4242
`.