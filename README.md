# DevJunior Academy - Site Web

Bienvenue sur le projet DevJunior Academy, une plateforme d'apprentissage pour les développeurs juniors.

## 🌐 Comment héberger ce site avec GitHub Pages

Ce site est configuré pour être hébergé **gratuitement** sur **GitHub Pages**. Voici comment cela fonctionne :

### 📋 Ce que j'ai fait pour configurer l'hébergement

1. **Créé un workflow GitHub Actions** (`.github/workflows/deploy.yml`)
   - Ce fichier automatise le déploiement du site à chaque modification
   - Il utilise les GitHub Actions officielles de GitHub pour Pages

### 🚀 Étapes pour activer GitHub Pages sur votre dépôt

1. **Allez dans les paramètres de votre dépôt** :
   - Cliquez sur l'onglet **Settings** (Paramètres) de votre dépôt GitHub

2. **Accédez à la section Pages** :
   - Dans le menu de gauche, cliquez sur **Pages** (sous "Code and automation")

3. **Configurez la source** :
   - Dans la section **Build and deployment**, sous **Source**, sélectionnez **GitHub Actions**

4. **Fusionnez cette PR dans main** :
   - Le workflow se lancera automatiquement après le merge
   - Vous pouvez suivre le déploiement dans l'onglet **Actions**

5. **Accédez à votre site** :
   - Une fois déployé, votre site sera accessible à l'adresse :
   - `https://VOTRE_USERNAME.github.io/NOM_DU_REPO/`
   - (Remplacez VOTRE_USERNAME et NOM_DU_REPO par vos valeurs)

### 🔄 Déploiement manuel

Vous pouvez également déclencher un déploiement manuellement :
1. Allez dans l'onglet **Actions**
2. Cliquez sur le workflow **Deploy static site to GitHub Pages**
3. Cliquez sur **Run workflow**

## 📁 Structure du projet

```
├── index.html          # Page principale du site
├── styles.css          # Styles CSS du site
├── script.js           # JavaScript pour l'interactivité
├── .github/
│   └── workflows/
│       └── deploy.yml  # Workflow de déploiement automatique
└── README.md           # Ce fichier
```

## 💡 Comment fonctionne le déploiement ?

Le fichier `.github/workflows/deploy.yml` contient un **workflow GitHub Actions** qui :

1. **Se déclenche** automatiquement à chaque push sur la branche `main`
2. **Récupère** le code source du dépôt
3. **Configure** GitHub Pages
4. **Télécharge** tous les fichiers du site (HTML, CSS, JS, images)
5. **Déploie** le site sur GitHub Pages

C'est entièrement automatique et gratuit !
