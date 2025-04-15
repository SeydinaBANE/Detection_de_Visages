# 🧠 Détection de Visages avec OpenCV

Ce projet vise à détecter automatiquement les visages présents dans une image à l'aide d'un **classificateur en cascade** (Haar Cascade) fourni par OpenCV. C’est un exemple concret d’application de la **vision par ordinateur** et des **mathématiques appliquées**.

## 📸 Résultats Observés

- ✅ **Image de Dan** : Un visage détecté avec succès.
- ⚠️ **Image de Barack Obama** : Deux faux positifs ont été détectés (zones confondues avec des visages).

Cela montre que bien que performant, le classificateur peut faire des erreurs, en particulier lorsque des motifs ressemblent à des visages.

---

## ⚙️ Fonctionnement du Projet

### 1. Prétraitement de l’image

- Conversion des images en **niveaux de gris** (le modèle fonctionne mieux ainsi).
- Utilisation des fonctions d’OpenCV pour charger, modifier et afficher les images.

### 2. Détection de visages

- Utilisation d’un **classificateur pré-entraîné** (`haarcascade_frontalface_default.xml`).
- La détection retourne les **coordonnées (x, y, largeur, hauteur)** de chaque visage trouvé.

### 3. Extraction et affichage

- Les visages détectés sont encadrés dans l’image.
- Possibilité d’extraire chaque visage et de le manipuler séparément.



