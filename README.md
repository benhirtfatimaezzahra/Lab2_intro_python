# Lab2 – Introduction à Python 

Ce projet regroupe trois exercices d’introduction à Python portant sur :
- Une mini-calculatrice interactive
- La conversion de températures
- L’analyse de texte utilisateur

Ces exercices permettent de pratiquer les bases essentielles : entrée utilisateur, conditions, conversions de types, manipulations de chaînes et gestion d’erreurs.


##  Contenu du projet

### 1️ Mini-calculatrice
Une calculatrice simple qui :
- Demande deux nombres (floats)
- Propose un menu d’opérations (+, -, *, /)
- Convertit les entrées en float
- Calcule le résultat en fonction de l’opérateur
- Gère les erreurs (valeurs incorrectes, division par zéro)
- Affiche le résultat via une f-string

**Fonctionnalités :**
- Addition, soustraction, multiplication, division
- Gestion propre des erreurs utilisateur
- Affichage du format : `4.5 * 2 = 9.0`

---

### 2️ Conversion de températures 
L’utilisateur choisit le sens de conversion :

- Celsius → Fahrenheit & Kelvin  
- Fahrenheit → Celsius & Kelvin  

**Formules utilisées :**
- `F = C × 9/5 + 32`
- `K = C + 273.15`
- `C = (F - 32) × 5/9`

**Fonctionnalités :**
- Menu interactif
- Vérification des erreurs (mauvaise saisie)
- Affichage formaté : `25°C = 77°F = 298.15K`

---

### 3️ Analyse de texte utilisateur 
L’utilisateur entre une phrase ou un mot, et le programme affiche :

- La longueur (`len`)
- Une version en majuscules (`upper()`)
- Une version en minuscules (`lower()`)
- La chaîne inversée (`[::-1]`)
- Le test palindrome (bonus)
- Explication sur l’immuabilité des strings en Python

---

##  Démonstration
Voici une vidéo illustrant le fonctionnement des trois exercices :



## 🚀 Installation & Exécution

### 1. Cloner la repo
```bash
git clone https://github.com/benhirtfatimaezzahra/Lab2_intro_python.git
