# Budget Tracker CLI
Python • SQLite • Command Line Interface

Application en ligne de commande permettant la gestion simple de dépenses et de recettes via SQLite.

Le projet est organisé en deux modules indépendants :
- Gestion des dépenses
- Gestion des recettes

Chaque module possède sa propre base de données locale.

---

## 📁 Structure du projet

BudgetTracker/
├── Depenses/
│   ├── depenses.py
│   └── base.db
│
└── Recettes/
    ├── recettes.py
    └── base.db

---

## ⚙️ Technologies utilisées

- Python 3
- SQLite3 (via le module standard `sqlite3`)
- Interface CLI (terminal)

---

## 🚀 Lancement

### Dépenses
```bash
cd Depenses
python depenses.py

### Recettes
```bash
cd Recettes
python recettes.py

MOT DE PASSE : test

🗄 Modèle de données
Chaque entrée contient :

Date (format jj/mm/aaaa)

Désignation (texte)

Montant (float)

Tables utilisées :

tt_donnees (Dépenses)

tt_donnees_r (Recettes)

🔐 Sécurité
Une authentification simple par mot de passe est requise au lancement du programme.

📌 Fonctionnalités
Ajout d’entrées avec date automatique

Affichage immédiat du contenu de la base

Suppression complète des données avec confirmation

Gestion dynamique via SQLite

🧠 Objectif du projet
Ce projet a été réalisé dans un objectif pédagogique afin de :

Manipuler SQLite avec Python

Comprendre la gestion de bases de données locales

Structurer une application CLI interactive

Travailler la gestion des entrées utilisateur et des boucles de contrôle
