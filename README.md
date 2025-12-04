# DevJunior Academy

Une plateforme d'apprentissage pour les développeurs juniors qui souhaitent maîtriser le développement web et l'informatique.

## 🚀 Déploiement sur GitHub Pages

Ce site est automatiquement déployé sur GitHub Pages grâce à un workflow GitHub Actions.

### Pour héberger ce projet :

1. **Activer GitHub Pages dans les paramètres du dépôt :**
   - Allez dans **Settings** > **Pages**
   - Sous **Source**, sélectionnez **GitHub Actions**

2. **Fusionner cette branche (ou pousser sur `main`)** :
   - Une fois fusionné sur `main`, le workflow de déploiement se lancera automatiquement

3. **Accéder au site :**
   - Votre site sera disponible à l'adresse : `https://<votre-nom-utilisateur>.github.io/Copilot_Mobile_app_test_SEO-AI_test/`

### Développement local

Pour tester le site localement, vous pouvez simplement ouvrir le fichier `index.html` dans votre navigateur, ou utiliser un serveur local :

```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js (npx)
npx serve .
```

## 📁 Structure du projet

- `index.html` - Page principale
- `styles.css` - Styles CSS
- `script.js` - Interactivité JavaScript
- `.github/workflows/deploy.yml` - Workflow de déploiement automatique
