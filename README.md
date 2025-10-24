# OneDeploy GitHub Tools

![GitHub release (latest by date)](https://img.shields.io/github/v/release/Tangui-Gouirand/PPT-ADDIN-MANAGER?label=version&color=blue)

[![Read in English](https://img.shields.io/badge/language-English-blue)](README.en.md)

**OneDeploy GitHub Tools** est un **gestionnaire centralisé** permettant à l’utilisateur de **configurer manuellement les dossiers** GitHub contenant ses compléments Office et exécutables, puis de **télécharger, installer, désinstaller et mettre à jour** ces outils via une interface simple, avec **vérification de signature numérique** intégrée.

<p align="center">
  <img src="https://github.com/user-attachments/assets/4eb8a72e-79ac-49f7-af98-e87282c43355" width="400"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e8092130-f05b-4012-bb80-82988c67d5b6" width="300"/>
</p>

---

## ✨ Fonctionnalités principales

- 📁 **Configuration manuelle** des dossiers GitHub contenant les outils (add-ins Office, exécutables)
- ✅ **Vérification automatique** des versions disponibles (via GitHub Releases)
- 🔘 **Mise à jour en un clic** : un bouton devient actif si une nouvelle version est détectée
- 🧹 **Désinstallation propre** des outils
- 🔒 **Vérification de signature** avant toute installation ou mise à jour

---

## 📦 Installation

1. Téléchargez la dernière version depuis la section [Releases](https://github.com/Tangui-Gouirand/PPT-ADDIN-MANAGER/releases).
2. Lancez l’exécutable `OneDeploy.exe`.
3. Au premier lancement, l’application se copie automatiquement dans :  
   `C:\Users\<User>\AppData\Local\Programs\ONEDEPLOY\`  
   et crée un raccourci vers cette version auto-gérée.

---

## ⚙️ Prérequis

- Windows 10 ou supérieur  
- Microsoft Office (PowerPoint, Word, Excel, Outlook à venir)  
- Connexion Internet (pour accéder aux dépôts GitHub)  

---

## 🛡️ Sécurité

Tous les fichiers téléchargés depuis GitHub sont :  
- Signés numériquement (`.sig`)  
- Vérifiés localement avant installation ou mise à jour  

---

## 📚 Roadmap

- [ ] Gestion des compléments Vsto  
- [ ] Support .exe 
- [ ] Gestion d’exécutables indépendants  
- [x] Interface de configuration avancée  
- [x] Détection automatique des dépôts (optionnel)  
- [x] Intégration proxy automatique
- [ ] Support multi-langue

---

## 🤝 Contribuer

Les contributions sont les bienvenues !  
Merci de soumettre un ticket ou une pull request via [Issues](https://github.com/Tangui-Gouirand/PPT-ADDIN-MANAGER/issues).

---

## 👤 Auteur

Développé par **Tangui Gouirand**  
