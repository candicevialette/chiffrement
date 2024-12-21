#🛡️ Découverte du Chiffrement avec AxCrypt et Thunderbird
![Banner](Image/background.png)

## 📄 **Description**

Ce dépôt contient des ressources dédiées à la découverte du chiffrement symétrique avec AxCrypt et du chiffrement asymétrique avec Thunderbird. Vous y trouverez des fichiers chiffrés, des guides pratiques et des exercices pour vous familiariser avec ces outils.

Cet atelier est conçu pour vous aider à développer des compétences dans la sécurisation des données et la gestion des communications chiffrées.
---

## 📚 **Qu'est-ce que le chiffrement avec AxCrypt et Thunderbird ?**

### AxCrypt

**AxCrypt** est un outil de chiffrement de fichiers conçu pour protéger vos données sensibles. Il offre une interface simple pour :

-**Chiffrer et déchiffrer des fichiers avec des mots de passe sécurisés.**

-**Partager des fichiers en toute sécurité avec d'autres utilisateurs.**

-**Assurer la confidentialité des données sensibles.**

### Thunderbird avec OpenPGP

**Thunderbird**, combiné avec **OpenPGP**, permet de chiffrer les communications par e-mail pour garantir leur confidentialité. C'est un outil puissant pour :

-**Protéger vos e-mails contre les interceptions.**

-**Signer numériquement vos messages pour prouver leur authenticité.**

-**Gérer des clés publiques et privées pour des échanges sécurisés.**
---

## 🔗 **Fonctionnalités Principales**

### AxCrypt

-**Chiffrement symétrique utilisant AES-128 ou AES-256** pour protéger les fichiers.

-**Partage sécurisé de fichiers avec des mots de passe.**

-**Interface intuitive** pour un usage facile.

### Thunderbird avec OpenPGP

-**Chiffrement asymétrique des e-mails** pour une confidentialité totale.

-**Gestion des clés publiques et privées** pour sécuriser les échanges.

-**Signatures numériques** pour valider l'origine des messages.

-**Interopérabilité avec d'autres clients OpenPGP** pour des échanges flexibles.
---

📂 Structure du Dépôt
```
📂 decouverte-packet-tracer/
|
├── 📂 Documents/
│   ├── 05_TP_Chiffrements symétrique et asymétrique.docx
│   └── 05_TP_Chiffrements symétrique et asymétrique.pdf
│
├── 📂 image/
│   └── background.png
|
└── README.md
```
---

## ⚙️ **Prérequis**

- **AxCrypt** et **Thunderbird** installés sur votre machine.

- [Télécharger AxCrypt](https://axcrypt.net/)

- [Télécharger Thunderbird](https://www.thunderbird.net/fr/)

- Connaissances de base sur les principes de sécurité des données :

- **chiffrement symétrique** (AES) et **Chiffrement asymétrique** (RSA, gestion des clés publiques et privées).
  ---

##🚀 **Mise en Œuvre**

### 1. ***Cloner le Dépôt***
```bash
git clone https://github.com/votre_nom_utilisateur/atelier-chiffrement.git
cd atelier-chiffrement
```
### 2. ***Parcourir la Documentation***

Consultez le dossier Documents/ pour des guides d'analyse détaillés sur l'utilisation d'AxCrypt et Thunderbird.

### 3. ***Pratique avec AxCrypt***

1. Lancez AxCrypt et créez un compte si ce n'est pas déjà fait.

2. Protégez des fichiers en suivant ces étapes :

3. Cliquez sur « Protéger » et sélectionnez un fichier ou un dossier.

4. Entrez un mot de passe sécurisé.

5. Envoyez le fichier chiffré à un destinataire tout en partageant le mot de passe de manière sécurisée.

### 4. ***Utilisation de Thunderbird avec OpenPGP***

1. Configuration initiale :

2. Paramétrez un compte e-mail sur Thunderbird.

3. Accédez aux paramètres de chiffrement pour activer OpenPGP.

4. Génération des clés :

Créez une paire de clés publique/privée dans les paramètres du compte.

Exportez votre clé privée pour une sauvegarde.

Partage de clés publiques :

Envoyez votre clé publique à un correspondant via un e-mail.

5. Échange de messages chiffrés :

Envoyez un message chiffré en utilisant la clé publique du destinataire.

Recevez et déchiffrez les messages avec votre clé privée.
---

## 👉 **Fonctionnalités Clés**

### AxCrypt

- **Protection des fichiers sensibles :** Utilisation de l’AES-128 pour un chiffrement sécurisé.

- **Interface intuitive :** Chiffrement et déchiffrement en quelques clics.

-**Partage de fichiers :** Possibilité de collaborer en partageant des fichiers chiffrés avec des mots de passe.

### Thunderbird avec OpenPGP

-**Chiffrement des e-mails :** Assurez la confidentialité de vos messages.

-**Signatures numériques :** Garantissez l’authenticité de vos correspondances.

-**Gestion des clés :** Créez, exportez et importez des clés publiques et privées.
---

##💡 **Bonnes Pratiques**

-**Sauvegardez vos clés privées** dans un endroit sécurisé.

-**Utilisez des mots de passe complexes** pour le chiffrement symétrique.

-**Vérifiez l’authenticité des clés publiques** avant de les utiliser.

-**Protocole de partage des mots de passe :** N’envoyez jamais un mot de passe par e-mail non chiffré.
---

## 📚 **Ressources Utiles**

- [Documentation AxCrypt](https://axcrypt.net/information/guides/get-started/)

-[Tutoriels Thunderbird](https://support.mozilla.org/fr/products/thunderbird)
- [Document OpenPGP](https://www.openpgp.org/)

Guide OpenPGP
---

🌍 Licence

Ce projet est sous licence MIT. Consultez le fichier LICENSE pour plus d'informations.
---

🕒 Date de Création

Décembre 2024

