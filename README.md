# 🎮 Morpion CLI

Une application de **Morpion (Tic-Tac-Toe)** jouable directement dans le terminal.

Ce projet a été développé en **Python 3** dans le cadre d'un apprentissage du développement logiciel assisté par IA avec **OpenCode**.

---

## 📖 Description

Le jeu permet à deux joueurs de s'affronter sur la même machine via une interface en ligne de commande.

Les joueurs jouent alternativement avec les symboles :

* ❌ Joueur 1
* ⭕ Joueur 2

L'application détecte automatiquement :

* 🏆 Les conditions de victoire
* 🤝 Les matchs nuls
* 🔄 La possibilité de rejouer une partie

---

## ✨ Fonctionnalités

* 🎯 Affichage d'une grille 3x3 dans le terminal
* 🔄 Alternance automatique des tours
* ✅ Validation des saisies utilisateur
* 🏆 Détection des victoires
* 🤝 Détection des matchs nuls
* 🔁 Possibilité de relancer une partie sans quitter le programme
* 🧪 Tests unitaires

---

## 🛠️ Technologies utilisées

* 🐍 Python 3
* 🧪 Pytest (tests unitaires)
* 🤖 OpenCode
* 📦 Git & GitHub

---

## 📂 Structure du projet

```text
jeu-morpion/
├── main.py
├── tests/
├── SPEC.md
├── README.md
└── .gitignore
```

---

## 🚀 Installation

### Cloner le dépôt

```bash
git clone https://github.com/syl566/jeu-morpion.git
cd jeu-morpion
```

### Vérifier Python

```bash
python3 --version
```

---

## ▶️ Lancer le jeu

```bash
python3 main.py
```

---

## 🧪 Exécuter les tests

Si `pytest` est installé :

```bash
pytest
```

Installation de pytest :

```bash
pip install pytest
```

ou

```bash
pip3 install pytest
```

---

## 📋 Règles du jeu

* Deux joueurs jouent chacun leur tour.
* Le premier joueur utilise le symbole **X**.
* Le second joueur utilise le symbole **O**.
* Le premier à aligner trois symboles horizontalement, verticalement ou diagonalement gagne la partie.
* Si la grille est remplie sans vainqueur, la partie est déclarée nulle.

---

## 🏗️ Méthodologie utilisée

Le projet a été réalisé selon le workflow suivant :

1. 📄 Rédaction d'un `SPEC.md`
2. 🧠 Planification de l'architecture
3. ⚙️ Implémentation progressive
4. 🔍 Revue du code
5. 🧪 Tests unitaires
6. 💾 Versionnement avec Git

---

## 🎯 Objectifs pédagogiques

* Comprendre la programmation procédurale en Python
* Structurer un projet simple
* Écrire du code lisible et maintenable
* Utiliser Git et GitHub
* Travailler efficacement avec un agent IA de développement

---

## 👨‍💻 Auteur

Projet réalisé dans le cadre d'une formation **Concepteur Développeur d'Applications (CDA)**.

Développé avec ❤️ et Python 🐍.
