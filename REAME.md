# MiniPython Compiler 🐍

<div align="center">
  <img src="assets/images/logo.png" alt="Logo MiniPython" width="200"/>
  <br>
  <b>Un compilateur léger pour un sous-ensemble du langage Python.</b>
</div>

---

## 📋 Table des Matières
1. [Introduction](#introduction)
2. [Fonctionnalités](#fonctionnalités)
3. [Pré-requis](#pré-requis)
4. [Installation et Usage](#installation-et-usage)
5. [Syntaxe du Langage](#syntaxe-du-langage)
6. [Auteurs](#auteurs)
7. [Licence](#licence)

## 📝 Introduction
[cite_start]Ce projet a été réalisé dans le cadre du module **Compilation 2** (4ème année Ingénieur, Spécialité Génie Logiciel) à l'Université de Tlemcen[cite: 8, 9].
L'objectif est de concevoir un compilateur pour le langage **MiniPython**, incluant l'analyse lexicale, syntaxique et sémantique.

## ✨ Fonctionnalités
Le langage MiniPython supporte les éléments suivants :
* [cite_start]**Types de données** : Entiers (`int`), Réels (`float`), Booléens (`bool`), Chaînes (`String`) et Tableaux (`int T[10]`, `float M[2][3]`)[cite: 28].
* [cite_start]**Opérations Arithmétiques** : Addition, multiplication, division, parenthèses (`+`, `.`, `*`, `/`)[cite: 30].
* [cite_start]**Opérations Booléennes** : ET, OU, NON (`&&`, `||`, `!`)[cite: 31].
* [cite_start]**Comparaisons** : Inferieur, Supérieur, Égal, Différent (`<`, `>`, `==`, `!=`)[cite: 32].
* [cite_start]**Structures de Contrôle** : Conditions `if`, `else` et boucles `while`[cite: 33, 38].
* [cite_start]**Procédures** : Définition de fonctions avec paramètres (`def procedure ... return`)[cite: 37].
* [cite_start]**Commentaires** : Multilignes utilisant `/* ... */`[cite: 39].

## ⚙️ Pré-requis
* [cite_start]**Python 3.8+** installé sur votre machine[cite: 24].
* [cite_start]Un éditeur de code comme **VS Code**[cite: 25].

## 🚀 Installation et Usage

1.  **Cloner le dépôt :**
    ```bash
    git clone [https://github.com/fadlboumaza/minipython-compiler.git](https://github.com/fadlboumaza/minipython-compiler.git)
    cd minipython-compiler
    ```

2.  **Lancer le compilateur :**
    Pour compiler un fichier source MiniPython (ex: `test.minipy`) :
    ```bash
    python main.py test.minipy
    ```

## 📚 Syntaxe du Langage

### Déclaration de variables
```c
int x;
float a;
bool b;
String s;
int T[10];      
float M[2][3];  
```

6.  **auteurs :**
    
    ```
    Hadbi Djamal
    Boussettine issam Eddine
    4eme ing (GL)
    module compilation
    aboubakr belkaid
    ```
7.  **date **
    
    ```bash
    16/12/2025
    ```
    
