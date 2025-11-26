
---

### 🔷 C. Repo `cpp-projects`

**Description GitHub** :  
> Projets C/C++ (RPG textuel, gestionnaire de tâches, exos Epitech)

**README.md :**

```md
# Projets C / C++

Ce dépôt regroupe plusieurs petits projets en C et C++ réalisés pour m'entraîner
à la programmation bas niveau, à la gestion de la mémoire, et à la conception orientée objet.

## 📦 Contenu

### 1. RPG textuel (C++)

- Système de personnages (Player, Enemy, Character)
- Gestion des statistiques (HP, attaque, défense, XP)
- Combat au tour par tour
- Inventaire et objets
- Sauvegarde/chargement possible (selon version)

Dossier : `rpg/`

### 2. Gestionnaire de tâches (C++)

- Ajout / suppression / édition de tâches
- Sauvegarde et chargement depuis un fichier
- Recherche et tri
- Menu interactif en console

Dossier : `task_manager/`

### 3. Exos C / Piscine Epitech (optionnel)

- Petits programmes en C
- Exercices d'algorithmie, manipulation de tableaux, chaînes, pointeurs, etc.

Dossier : `epitech_exos/`

## 🛠️ Compilation (exemple)

```bash
cd rpg
g++ -std=c++20 -O2 -o rpg main.cpp
./rpg
