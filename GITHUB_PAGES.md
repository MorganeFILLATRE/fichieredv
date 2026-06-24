# 🚀 Guide de déploiement sur GitHub Pages

## Option 1 : Déploiement rapide (Recommandé)

### Étape 1 : Créer un dépôt GitHub

1. Allez sur **github.com**
2. Cliquez sur **"New"** (nouveau dépôt)
3. Nommez-le : `examen-optometrique` (ou autre)
4. Sélectionnez **Public**
5. Cliquez **Create repository**

### Étape 2 : Ajouter les fichiers

Vous avez 3 façons :

#### Méthode A : Via l'interface GitHub

1. Cliquez sur **Add file > Upload files**
2. Uploadez :
   - `index.html`
   - `README.md`
   - `.gitignore`
3. Cliquez **Commit changes**

#### Méthode B : Via Git en ligne de commande

```bash
# Clonez le dépôt
git clone https://github.com/VOTRE-USERNAME/examen-optometrique.git
cd examen-optometrique

# Copiez les fichiers dans ce dossier
# (index.html, README.md, .gitignore)

# Ajoutez et commitez
git add .
git commit -m "Initial commit: Application examen optométrique"
git push origin main
```

### Étape 3 : Activer GitHub Pages

1. Allez dans **Settings** du dépôt
2. Allez dans **Pages** (menu gauche)
3. Sous **Source**, sélectionnez **main**
4. Sélectionnez le dossier **root**
5. Cliquez **Save**

⏳ **Attendez 1-2 minutes**

Votre application sera accessible à :
```
https://VOTRE-USERNAME.github.io/examen-optometrique/
```

## Option 2 : Structure avancée

Si vous voulez une meilleure organisation :

```
examen-optometrique/
├── index.html           # Application principale
├── README.md            # Documentation
├── .gitignore           # Fichiers à ignorer
├── docs/
│   ├── INSTALLATION.md
│   └── GUIDE.md
└── assets/
    ├── logo.png
    └── screenshots/
```

## Option 3 : Déployer ailleurs

### Sur Vercel (gratuit, très rapide)

1. Allez sur **vercel.com**
2. Connectez votre GitHub
3. Sélectionnez le dépôt
4. Cliquez **Deploy**

Votre app sera à : `https://votre-app.vercel.app`

### Sur Netlify (gratuit)

1. Allez sur **netlify.com**
2. Cliquez **New site from Git**
3. Connectez GitHub
4. Sélectionnez le dépôt
5. Laissez les paramètres par défaut
6. Cliquez **Deploy**

Votre app sera à : `https://votre-app.netlify.app`

## 📱 Utilisation après déploiement

### Depuis vos opticiens

1. **Donnez l'URL** de votre application
   ```
   https://votre-username.github.io/examen-optometrique/
   ```

2. **Ils peuvent :**
   - Saisir les données d'examen
   - Exporter en Excel
   - Générer des rapports
   - Tout fonctionne offline !

### Pour accéder depuis plusieurs appareils

- Sur **PC** : Ouvrir le lien dans le navigateur
- Sur **Téléphone/Tablette** : Même lien, adaptation mobile automatique
- **Offline** : Une fois chargée, fonctionne sans internet

## 🔄 Mise à jour de l'application

### Si vous voulez modifier l'app :

1. Modifiez `index.html` en local
2. Uploadez via Git :
   ```bash
   git add index.html
   git commit -m "Modification: [description des changements]"
   git push origin main
   ```
3. GitHub Pages se mettra à jour automatiquement (30 sec)

## 🛠️ Personnalisation facile

### Changer les couleurs

Dans `index.html`, cherchez :
```
#0066cc  → Bleu principal
#0099ff  → Bleu dégradé
#27ae60  → Vert (bouton Sauvegarder)
```

Remplacez par vos codes couleur préférés.

### Ajouter un logo

Cherchez :
```html
<h1 style="...">👁️ Examen Optométrique</h1>
```

Remplacez l'emoji par un HTML image :
```html
<img src="logo.png" style="height: 40px;"> Examen Optométrique
```

## 📊 Statistiques & Suivi

GitHub vous donne accès à :
- Nombre de visites (via Google Analytics si vous le souhaitez)
- Qui a cliqué où
- Performance

## ❓ Problèmes courants

### L'app ne charge pas

- ✅ Vérifiez l'URL exacte
- ✅ Attendez 1-2 minutes si c'est récent
- ✅ Nettoyez le cache du navigateur
- ✅ Essayez avec un autre navigateur

### Les données ne se sauvegardent pas

- ✅ Assurez-vous que les cookies/localStorage sont activés
- ✅ Testez dans une fenêtre non-privée
- ✅ Vérifiez que vous avez de l'espace disque

### Les exports Excel ne fonctionnent pas

- ✅ Essayez avec un autre navigateur
- ✅ Vérifiez que JavaScript est activé
- ✅ Attendez quelques secondes après le chargement

## 🎉 C'est prêt !

Votre application est maintenant :
- ✅ En ligne et accessible 24/7
- ✅ Sans frais d'hébergement
- ✅ Automatiquement mis à jour
- ✅ Sécurisée (HTTPS gratuit)

**Partagez le lien avec vos équipes et commencez à saisir des examens !**

---

Questions ? Besoin de modifications ? Contactez un développeur.
