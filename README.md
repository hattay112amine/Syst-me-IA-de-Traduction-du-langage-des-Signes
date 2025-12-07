# 🧠 Système IA de Traduction du Langage des Signes  
### Une application intelligente pour rendre la communication plus accessible

## 📌 Description du Projet  
Ce projet consiste en la création d'une **application de bureau** basée sur l'intelligence artificielle, dont l’objectif est de faciliter la communication pour les **personnes sourdes et malentendantes**.

Le système utilise des technologies avancées en **apprentissage profond**, **LSTM**, et **vision par ordinateur** pour **traduire en temps réel** les gestes du **Langage des Signes Tunisien (LST)** en texte écrit.

🎯 **Objectif principal :** offrir une solution **accessible**, **précise**, **fluide** et **utilisable en temps réel**, contribuant ainsi à l’inclusion sociale.

---

## 🏗️ Architecture & Aperçus

### 📌 Architecture du modèle LSTM
<img width="777" height="460" alt="architecture_LSTM" src="https://github.com/user-attachments/assets/a5ff6c4f-4704-40fd-8dbc-1d1ffa883523" />

### 📌 Exemple de prédiction d’un signe
<img width="911" height="586" alt="prediction_d'un signeenmot" src="https://github.com/user-attachments/assets/0881382f-4970-4b0b-bd7e-cacdb8712da8" />

### 📌 Interface graphique du système
<img width="1357" height="716" alt="Capture d&#39;écran 2025-05-19 195001" src="https://github.com/user-attachments/assets/95a1b5a0-e762-4260-8ad3-b0a0a1b154db" />

### 📌 Diagramme d’activité du fonctionnement général
<img width="1359" height="766" alt="diagramme_d'activitéssur le fonctionnement géneral sy sytéme" src="https://github.com/user-attachments/assets/0504a45a-860c-45df-92fb-d45fac903982" />

---

## 🚀 Fonctionnalités Principales

### **1️⃣ Mode En Ligne (Visioconférence)**  
✔ Traduction **en temps réel** des gestes en texte  
✔ Intégration transparente avec Zoom / Teams via **caméra virtuelle OBS**  
✔ Génération automatique de **sous-titres en direct**

---

### **2️⃣ Mode Hors Ligne (Standalone / Local)**  
✔ Traduction en temps réel à partir de la **webcam**  
✔ Traduction à partir de **fichiers vidéo importés**  
✔ Fonctionne **sans connexion Internet**  
✔ Modèle IA exécuté en local → **performances rapides et confidentialité garantie**

---

## 🔐 Fonctionnalités Transverses  
- Création de compte + Authentification utilisateur  
- Historique des traductions  
- Taux de reconnaissance visé : **> 95 %**  
- Interface intuitive et adaptée aux non-techniciens

---

## 🛠️ Technologies Utilisées

### **🧩 Backend & IA**  
- Python  
- TensorFlow / Keras (LSTM, Deep Learning)  
- Mediapipe (détection des landmarks)  
- OpenCV (vision par ordinateur)

### **🧩 Interface (Desktop App)**  
- Tkinter / CustomTkinter  
- Architecture en couches (monolithique)

### **🧩 Outils complémentaires**  
- OBS (caméra virtuelle pour visioconférence)  
- JSON, NumPy, Pandas  
