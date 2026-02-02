# Système de Surveillance Intelligent des Comportements à Risque chez les Personnes Âgées

# Système de Surveillance Intelligent

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-1.x-FF4B4B?logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/YOLOv8-8.x-FF6C37?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAoAAAAKCAYAAACNMs+9AAAAF0lEQVQYV2NggAKGBgYmBgYGBiYGAAAwAE9+CBcUAAAAASUVORK5CYII=" />
  <img src="https://img.shields.io/badge/OpenCV-4.x-5C3EE8?logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/SVM-Linear%2FRBF-6F42C1?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/RandomForest-Tree-4B8BBE?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/CNN-Convolutional-FF6F61?logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/LSTM-Recurrent-FF6F61?logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-2.x-EE4C2C?logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit-learn-1.x-F7931E?logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-2.x-FF6F00?logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/ReadTheDocs-3.x-007ACC?logo=read-the-docs&logoColor=white" />
</p>


Dans le cadre de ce projet, nous avons développé un **système de surveillance intelligent** pour **surveiller les comportements des personnes** en utilisant le **traitement d'images et de vidéos**. Plusieurs jeux de données ont été collectés, provenant de sites spécialisés en **détection de chutes** et de **Kaggle**, afin d’entraîner nos modèles.

## Modèles Implémentés

- **CNN** : analyse l’évolution **spatiale** des images.  
- **LSTM** : capture l’évolution **temporelle** pour la **prédiction de chutes**.  
- **YOLOv8** : détection en temps réel des **chutes**.  
- **SVM & Random Forest** : détection de la **fatigue et de la somnolence**.

## Application

Une **application interactive** a été créée avec **Streamlit**, offrant une surveillance **en temps réel** basée sur la **vision par ordinateur**, pour détecter les **chutes**, la **somnolence**, et **prévoir les chutes imminentes**, dans le but d’**améliorer la sécurité et la qualité de vie des personnes**.


---

##  Description du Projet

Ce projet propose une surveillance **non intrusive** en temps réel, en combinant plusieurs modèles d’intelligence artificielle pour détecter des situations à risque :

-  **Somnolence** (fatigue visuelle via EAR & MAR)
-  **Prédiction de chute** (séquences vidéo)
-  **Détection de chute** (basée sur YOLOv5)

Le système fournit des **alertes instantanées** (visuelles et sonores) pour prévenir les accidents domestiques ou les postures critiques.

---

##  Fonctionnalités

### 🔹 1. Détection de Somnolence
- Analyse des yeux (EAR) et de la bouche (MAR)
- Classification : **Actif** ou **Somnolent**
- Détection en temps réel avec suivi vidéo

### 🔹 2. Prédiction de Chute
- Analyse de séquences vidéo pour prédire les risques
- Utilise des modèles entraînés sur des vidéos 
- Résultat affiché avant qu’une chute ne survienne

### 🔹 3. Détection de Chute
- Utilisation de **YOLOv5** pour détecter les chutes en direct
- Encadrement de la personne avec un label "Fall" ou "Normal"
- Détection rapide dans des vidéos en live ou enregistrées

### 🔹 4. Interface Utilisateur
- Application **Streamlit** intuitive
- Choix entre :
  - Mode **Vidéo** (analyse de fichiers)
  - Mode **Live** (caméra en direct)
- Visualisation des résultats et alertes en temps réel

---
Pour plus de détails sur le projet et les tutoriels associés, consultez la documentation complète ici :  
[Computer Vision Project Documentation](https://computer-vision2.readthedocs.io/en/latest/)

## Organisation du Dépôt

```bash
├── app.py                      # Interface principale Streamlit
├── models/                     # Modèles entraînés
│   ├── yolov5_fall.pt          # Détection de chutes (YOLOv5)
│   ├── drowsiness_model.h5     # Détection de somnolence
│   └── fall_prediction.h5      # Prédiction de chute
├── notebooks/                  # Notebooks pour entraînement et tests
│   ├── train_drowsiness.ipynb
│   ├── train_fall_prediction.ipynb
│   └── test_yolov5.ipynb
├── utils/                     
├── alert.mp3                   # Son d’alerte
├── README.md
└── requirements.txt            # Dépendances du projet
```

## Contact

## Contact

Je suis disponible pour toute **collaboration**, **assistance** ou **maintenance de projets**.  
Vous pouvez me contacter via mon site web : [https://site-web-nodemailer.vercel.app](https://site-web-nodemailer.vercel.app)

Cordialement,  
**Hinimdou Morsia Guitdam**


