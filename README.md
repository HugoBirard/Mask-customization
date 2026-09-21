# 🎭 Custom Mask Generator

> Un projet de création et de personnalisation de masques sur-mesure, de la conception 2D modulaire jusqu'à l'export 3D prêt pour l'impression, propulsé par **Python** et le web.

---

## 🚀 À propos du projet

Ce projet a pour objectif de proposer une interface interactive de personnalisation de masques. L'utilisateur dispose d'un panneau de contrôle à gauche pour choisir les différentes parties (bouches, yeux, cornes, couleurs) et observe le rendu du masque s'ajuster en temps réel sur la zone de droite.

L'architecture repose sur une séparation moderne : un back-end en **Python** pour gérer les assets et la logique, et une interface web (HTML/CSS/JS) pour l'interactivité fluide.

---

## ✨ Fonctionnalités prévues

* **Interface interactive :** Barre de choix modulaire à gauche et prévisualisation visuelle en temps réel à droite.
* **Personnalisation par zone :** Choix des yeux, de la bouche, des cornes et des teintes/couleurs.
* **Export & Téléchargement :**
  * *Version 2D :* Téléchargement de la composition finale sous forme d'image ou de calques vectoriels.
  * *Version 3D (Objectif final) :* Assemblage et génération de fichiers 3D (`.STL`) optimisés pour l'impression 3D.

---

## 🗺️ Fiche de route (Roadmap)

### Étape 1 : Maquette et Interface (Front-end)
- [ ] Créer la structure de la page avec un layout en deux colonnes (Panneau de choix à gauche, zone de rendu à droite).
- [ ] Styliser l'interface (avec Tailwind CSS ou CSS pur) pour un design propre et ergonomique.
- [ ] Intégrer les premiers éléments visuels (images ou SVG de test pour les yeux, bouches et cornes).

### Étape 2 : Le Cerveau Python (Back-end)
- [ ] Configurer un serveur léger avec **FastAPI** (ou Flask) en Python.
- [ ] Structurer le dossier d'assets pour stocker les morceaux graphiques (calques 2D, puis fichiers 3D STL).
- [ ] Mettre en place des routes API pour communiquer les listes de pièces disponibles au site web.

### Étape 3 : Interactivité et Temps Réel
- [ ] Coder la logique en JavaScript pour que chaque clic sur la barre de gauche mette à jour instantanément le rendu à droite.
- [ ] Gérer dynamiquement les couleurs et l'assemblage des calques.

### Étape 4 : Passage à la 3D & Impression 3D
- [ ] Intégrer un visualiseur 3D dans le navigateur (ex: Three.js).
- [ ] Utiliser une bibliothèque Python (ex: Trimesh) côté serveur pour fusionner les pièces 3D sélectionnées lors du téléchargement.

---

## 🛠️ Stack technique envisagée

* **Back-end :** Python (FastAPI / Flask)
* **Front-end :** HTML5, CSS3 / Tailwind CSS, JavaScript (Vanilla)
* **Affichage :** SVG / Canvas (pour la 2D) puis Three.js / WebGL (pour la 3D)

---

## ⚙️ Installation et lancement

*(Les instructions d'installation détaillées seront ajoutées au fur et à mesure de l'avancée du code).*

---

## 🤝 Contribution

Les suggestions, idées de design ou contributions sont les bienvenues ! N'hésite pas à ouvrir une *Issue* ou à proposer une *Pull Request*.

---

## 📄 Licence

Ce projet est sous licence [MIT](LICENSE).
