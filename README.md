# File Upload Web Application

Application web développée avec Node.js et Express permettant le téléversement et la gestion d’images via une interface moderne et responsive.

## Fonctionnalités principales

- Téléversement d’images
- Upload de plusieurs fichiers
- Prévisualisation des images
- Validation des extensions de fichiers
- Limitation de la taille des uploads
- Stockage local des fichiers
- Gestion des erreurs serveur
- Interface utilisateur responsive

---

## Technologies utilisées

- Node.js
- Express.js
- Multer
- HTML5
- CSS3
- JavaScript

---

## Installation du projet

### 1. Créer le dossier du projet

```bash
mkdir file-upload-app
cd file-upload-app
```

---

### 2. Initialiser le projet Node.js

```bash
npm init -y
```

---

### 3. Installer les dépendances

```bash
npm install express multer
```

---

## Structure du projet

```bash
file-upload-app/
│
├── public/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
│
├── uploads/
│
├── views/
│   ├── index.html
│   └── success.html
│
├── server.js
└── package.json
```

---

## Lancement du serveur

```bash
node server.js
```

ou avec Nodemon :

```bash
npx nodemon server.js
```

---

## Accès à l’application

Ouvrir dans le navigateur :

```bash
http://localhost:3000
```

---

## Fonctionnement général

1. Sélection d’une ou plusieurs images
2. Envoi du formulaire
3. Traitement des fichiers avec Multer
4. Sauvegarde dans le dossier `uploads`
5. Affichage du résultat

---

## Sécurité et validation

Le projet inclut :

- Validation des formats d’images
- Limitation de taille des fichiers
- Gestion des erreurs d’upload
- Protection contre les fichiers invalides

---

# Résultat


https://github.com/user-attachments/assets/bfe4240d-afc1-4e48-9e92-059bd2762cad


---

## Auteur

Projet réalisé avec Node.js et Express.js dans le cadre d’un exercice pratique sur la gestion des fichiers.
