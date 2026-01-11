
---

# 📱 Lab 1 – Structure de base et composants UI avec React Native (Expo)

Ce projet a pour objectif d’initier à la création d’une application mobile avec **React Native + Expo**, en mettant l’accent sur :

* La structure d’un projet Expo
* La création de composants réutilisables
* L’organisation du code dans un dossier `components`
* L’utilisation du layout avec `flex` et `View`

---

## 🚀 Prérequis

* Node.js (version LTS)
* npm ou yarn
* Expo CLI (installé automatiquement via `npx`)
* Application **Expo Go** sur smartphone ou un émulateur Android / iOS

---

## 🛠️ Installation du projet

```bash
npx create-expo-app premier-component-rn
cd premier-component-rn
npx expo start
```

---

## 📂 Structure du projet

```
premier-component-rn/
 ├── App.js
 ├── components/
 │     ├── AppHeader.js
 │     └── AppFooter.js
 └── assets/
```

---

## 🧩 Composants

### 🔹 AppHeader

Affiche un en-tête avec :

* Titre de l’application
* Sous-titre descriptif

### 🔹 AppFooter

Affiche un pied de page contenant :

* Le texte *All rights reserved, 2025*

---

## 🏗️ Assemblage dans App.js

Le fichier `App.js` assemble les composants ainsi :

* **AppHeader** en haut
* Une vue centrale pour le contenu principal
* **AppFooter** en bas

Grâce à `flex:1`, l’écran est réparti verticalement de façon fluide.

---

## 📱 Résultat attendu

* Un header jaune en haut
* Un texte blanc centré au milieu
* Un footer jaune en bas

---

## 🎯 Mini-défis (Extensions)

* Ajouter l’année dynamique dans le footer
* Personnaliser le texte du header
* Créer un troisième composant `MainCard` pour afficher une carte centrale

---

## 📚 Objectifs pédagogiques

À la fin de ce lab, l’étudiant sera capable de :

* Créer un projet React Native avec Expo
* Comprendre le rôle de `App.js`
* Créer et utiliser des composants réutilisables
* Structurer proprement une application mobile

---
