# Hangman Web

Ce projet est une application web du jeu du pendu, permettant aux utilisateurs de deviner des mots dans différentes catégories. L'application offre une interface simple et interactive pour jouer au jeu directement depuis un navigateur.

## Fonctionnalités

- **Choix des catégories** : Sélectionnez une catégorie parmi les noms de personnages, planètes ou races.
- **Interface interactive** : Jouez au jeu du pendu avec une interface utilisateur intuitive.
- **Gestion des erreurs** : Affiche les lettres incorrectes et le nombre d'essais restants.
- **Dictionnaire extensible** : Les mots sont stockés dans des fichiers texte, ce qui permet d'ajouter facilement de nouvelles catégories ou mots.

## Technologies utilisées

- **Frontend** : HTML, CSS
- **Backend** : Go (Golang)
- **Fichiers de données** : Les mots sont stockés dans des fichiers texte dans le dossier `dico`.

## Installation

1. Accédez au dossier du projet :
    ```bash
    cd hangman_web
    ```
2. Assurez-vous d'avoir Go installé sur votre machine. Si ce n'est pas le cas, téléchargez-le depuis [golang.org](https://golang.org/).
3. Lancez l'application :
    ```bash
    go run hangman.go
    ```
4. Accédez à l'application via votre navigateur à l'adresse :
    ```
    http://localhost:8080
    ```

## Contribution

Les contributions sont les bienvenues ! Si vous souhaitez contribuer, veuillez soumettre une pull request ou ouvrir une issue pour discuter des changements.

## Auteurs

- **Raven** - Développeur principal

## Remerciements

Un grand merci à toutes les ressources open-source et aux outils qui ont permis de réaliser ce projet.