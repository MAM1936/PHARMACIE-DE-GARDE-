# 📚 Guide d'Installation et de Déploiement

## 🌐 Méthode 1 : GitHub Pages (Recommandé)

### Étape 1 : Créer un compte GitHub
1. Allez sur [github.com](https://github.com)
2. Cliquez sur "Sign up"
3. Créez votre compte gratuitement

### Étape 2 : Créer un nouveau repository
1. Une fois connecté, cliquez sur le bouton "+" en haut à droite
2. Sélectionnez "New repository"
3. Nommez votre repository (ex: `pharmacies-garde-ci`)
4. Cochez "Public"
5. Cochez "Add a README file"
6. Cliquez sur "Create repository"

### Étape 3 : Uploader les fichiers
1. Dans votre repository, cliquez sur "Add file" → "Upload files"
2. Glissez-déposez ces fichiers :
   - `index.html` (page d'accueil)
   - `pharmacies.html` (application publique)
   - `admin.html` (interface admin)
   - `README.md` (documentation)
3. Cliquez sur "Commit changes"

### Étape 4 : Activer GitHub Pages
1. Dans votre repository, cliquez sur "Settings"
2. Dans le menu de gauche, cliquez sur "Pages"
3. Sous "Source", sélectionnez "main" branch
4. Cliquez sur "Save"
5. Attendez quelques minutes

### Étape 5 : Accéder à votre site
Votre site sera accessible à l'adresse :
```
https://votre-username.github.io/pharmacies-garde-ci/
```

---

## 🚀 Méthode 2 : Netlify (Très Simple)

### Étape 1 : Créer un compte
1. Allez sur [netlify.com](https://netlify.com)
2. Créez un compte gratuit

### Étape 2 : Déployer
1. Cliquez sur "Add new site" → "Deploy manually"
2. Glissez-déposez le dossier contenant vos fichiers
3. C'est tout ! Votre site est en ligne

Netlify vous donnera une URL gratuite comme :
```
https://nom-aleatoire.netlify.app
```

Vous pouvez personnaliser le nom dans les paramètres.

---

## 💻 Méthode 3 : Hébergement Local (Pour tester)

### Sur Windows
1. Placez les fichiers dans un dossier
2. Double-cliquez sur `index.html`
3. Le site s'ouvre dans votre navigateur

### Sur Mac/Linux
1. Ouvrez le Terminal
2. Naviguez vers votre dossier :
   ```bash
   cd /chemin/vers/votre/dossier
   ```
3. Lancez un serveur local :
   ```bash
   python3 -m http.server 8000
   ```
4. Ouvrez votre navigateur à : `http://localhost:8000`

---

## 🔧 Personnalisation

### Changer les couleurs
Dans les fichiers HTML, recherchez ces valeurs dans les sections `<style>` :
- `#667eea` - Couleur principale (violet)
- `#764ba2` - Couleur secondaire (violet foncé)

Remplacez par vos propres couleurs.

### Ajouter votre logo
Dans `index.html`, remplacez :
```html
<div class="logo">🏥</div>
```
Par :
```html
<img src="votre-logo.png" alt="Logo" style="max-width: 200px;">
```

### Ajouter d'autres villes
1. Ouvrez `admin.html`
2. Recherchez :
```html
<option value="Abidjan">Abidjan</option>
<option value="Grand-Bassam">Grand-Bassam</option>
```
3. Ajoutez vos villes :
```html
<option value="Yamoussoukro">Yamoussoukro</option>
<option value="Bouaké">Bouaké</option>
```

---

## 📱 Partage de l'application

Une fois en ligne, vous pouvez :
- Partager le lien sur WhatsApp
- Créer un QR Code pointant vers votre site
- Ajouter le lien sur vos réseaux sociaux

### Créer un QR Code
1. Allez sur [qr-code-generator.com](https://www.qr-code-generator.com)
2. Collez l'URL de votre site
3. Téléchargez le QR Code
4. Partagez-le sur vos supports de communication

---

## 🆘 Support et Problèmes

### Le site ne s'affiche pas
- Vérifiez que tous les fichiers sont bien uploadés
- Attendez 5-10 minutes après activation de GitHub Pages
- Videz le cache de votre navigateur (Ctrl+F5)

### Les données ne se sauvegardent pas
- Vérifiez que votre navigateur autorise localStorage
- N'utilisez pas le mode navigation privée

### La carte ne s'affiche pas
- Vérifiez votre connexion internet
- Leaflet nécessite une connexion pour charger les tuiles de carte

---

## 📈 Prochaines Étapes

### Phase 1 - Actuellement ✅
- Interface publique
- Interface admin
- Carte interactive
- Recherche et filtres

### Phase 2 - À venir
- [ ] Base de données en ligne (Firebase)
- [ ] Système de notifications
- [ ] Application mobile
- [ ] API REST

### Phase 3 - Futur
- [ ] Partage sur réseaux sociaux
- [ ] Itinéraires GPS
- [ ] Avis et commentaires
- [ ] Multi-langues (Français/Anglais)

---

## 💡 Conseils

1. **Testez localement d'abord** avant de déployer
2. **Sauvegardez vos données** régulièrement (exportez localStorage)
3. **Mettez à jour régulièrement** les informations des pharmacies
4. **Communiquez** : Partagez largement l'URL de votre application

---

## 🎯 Objectifs

L'objectif est de faciliter l'accès aux pharmacies de garde pour tous les citoyens de Côte d'Ivoire. Votre contribution aide la communauté !

---

**Besoin d'aide ?** N'hésitez pas à consulter la documentation GitHub ou Netlify.

**Bonne chance ! 🚀**
