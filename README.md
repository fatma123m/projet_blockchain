# TP 8 : Blockchain & Application Décentralisée (DApp) avec Flutter

Ce projet est une Application Décentralisée (DApp) "Hello World" réalisée dans le cadre du TP 8. Elle permet de lire et d'écrire des données (un nom) sur une blockchain Ethereum locale (Ganache) via une interface utilisateur Flutter.

## 🚀 Fonctionnalités

* **Connexion Blockchain :** Communication en temps réel avec Ganache via WebSockets (`ws://`) et HTTP (`http://`).
* **Smart Contract :** Contrat Solidity `HelloWorld.sol` pour stocker l'état.
* **Lecture :** Récupération du nom stocké sur la blockchain.
* **Écriture :** Modification du nom via une transaction signée (nécessite du Gas).
* **Compatibilité :** Détection automatique de l'ID du réseau (Chain ID) pour fonctionner aussi bien sur `1337` que `5777`.

## 🛠️ Technologies utilisées

* **Frontend :** Flutter (Dart)
* **Blockchain :** Ganache (Réseau Ethereum local)
* **Smart Contract :** Solidity (v0.5.9)
* **Framework Blockchain :** Truffle
* **Librairies Dart :** `web3dart`, `provider`, `web_socket_channel`

---

## 📋 Prérequis pour tester

Pour lancer ce projet, vous devez avoir installé :
1.  **Flutter SDK** (Version 3.x recommandée)
2.  **Ganache** (Interface graphique)
3.  **Truffle** (`npm install -g truffle`)

---

## ⚙️ Installation et Configuration (Important)

### 1. Cloner le projet
```bash
git clone [https://github.com/fatma123m/projet_blockchain.git](https://github.com/fatma123m/projet_blockchain.git)
cd projet_blockchain
