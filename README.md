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
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/06f47ea5-836e-4127-a394-37600ac07801" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c89a6e71-a805-4207-b196-476cbe30f243" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9817730a-2ee0-480e-adf5-10a8ca8b640e" />

##  Installation & Exécution

### 1. Cloner la repo
```bash
git clone https://github.com/benhirtfatimaezzahra/Lab2_intro_python.git
```

### 2. Ouvrir les notebooks

Depuis Jupyter Notebook, VS Code ou Google Colab, ouvrez :

- `Mini-calculatrice.ipynb`
- `Conversion de températures.ipynb`
- `Analyse de texte utilisateur.ipynb`

### 3. Exécuter les cellules

Chaque notebook contient un exercice autonome.



##  Auteur

**Nom :** Benhirt Fatima Ezzahra  
**Cours :** Introduction à Python  
**Date :** Novembre 2025  
**Encadré par :** Pr. Mohamed LACHGAR  

