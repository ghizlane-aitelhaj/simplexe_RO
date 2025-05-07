# Optimisation Linéaire - Flask App

Ce projet est une application web développée avec Flask permettant de résoudre des problèmes d'optimisation linéaire. Elle implémente deux méthodes :
1. **Méthode du Simplexe** : Résout les problèmes de programmation linéaire en tableau.
2. **Méthode géométrique** : Résout les problèmes de programmation linéaire à 2 variables à l'aide de graphiques.

## Fonctionnalités
- Résolution des problèmes d'optimisation linéaire avec les méthodes du Simplexe et géométrique.
- Affichage du tableau du Simplexe étape par étape.
- Graphiques générés via Matplotlib pour visualiser les contraintes et la solution optimale.
- Interface utilisateur simple via Flask pour entrer les données du problème (coefficients, contraintes).

## Prérequis
- Python 3.x
- Flask
- Matplotlib
- NumPy

## Installation

1. Clone ce dépôt :

    ```bash
    git clone https://github.com/ton-utilisateur/ton-projet.git
    ```

2. Installe les dépendances :

    ```bash
    pip install -r requirements.txt
    ```

3. Lance l'application :

    ```bash
    python app.py
    ```

4. Accède à l'application sur [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

## Utilisation

- Sur la page d'accueil, entre les dimensions du problème.
- Ensuite, saisis les coefficients de la fonction objectif et les contraintes.
- Choisis la méthode de résolution (Simplexe ou Géométrique).
- Le résultat sera affiché sous forme de tableau ou graphique selon la méthode choisie.

## Contribution

1. Fork ce dépôt.
2. Crée une branche (`git checkout -b feature-nouvelle-fonctionnalité`).
3. Commit tes changements (`git commit -am 'Ajoute une nouvelle fonctionnalité'`).
4. Pousse vers le dépôt distant (`git push origin feature-nouvelle-fonctionnalité`).
5. Crée une Pull Request.

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus d'informations.
