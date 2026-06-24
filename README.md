# 👁️ Application Examen Optométrique

Une application web moderne et intuitive pour faciliter la saisie des données d'examen optométrique par vos équipes d'opticiens.

## ✨ Fonctionnalités

- 📋 **Formulaire complet** : Toutes les données d'examen structurées en 7 sections logiques
- 💾 **Sauvegarde locale** : Les données restent sur l'ordinateur de l'opticien
- 📊 **Export Excel** : Génération automatique de fichiers `.xlsx` pour archivage
- 📄 **Rapport professionnel** : Création de comptes-rendus formatés pour ophtalmologiste
- ⚡ **Rapide et fluide** : Optimisée pour 10-50 examens par jour
- 🌐 **Pas d'installation** : Fonctionne directement dans le navigateur

## 🚀 Installation & Utilisation

### Option 1 : Utilisation directe (Recommandée) 🌟

1. **Téléchargez** le fichier `index.html`
2. **Double-cliquez** dessus pour l'ouvrir dans votre navigateur
3. C'est prêt ! Aucune installation nécessaire.

### Option 2 : Sur GitHub Pages

1. Créez un dépôt GitHub avec ce fichier
2. Allez dans **Settings > Pages**
3. Activez GitHub Pages
4. Votre application sera accessible via : `https://votre-username.github.io/votre-repo/`

### Option 3 : Déploiement sur un serveur web

```bash
# Copiez le fichier index.html sur votre serveur web
# Accédez-le via : https://votre-domaine.com/index.html
```

## 📖 Guide d'utilisation

### Structure du formulaire

L'application est organisée en **7 onglets** :

1. **📋 Infos Patient**
   - Date d'examen
   - Nom et prénom
   - Date de naissance
   - Origine de l'EDV (client, Priscilla, JDP)
   - Initiales de l'opticien

2. **🏥 Anamnèse**
   - But de la visite
   - Plaintes visuelles
   - Santé oculaire (pathologies, chirurgies, etc.)
   - Santé générale (diabète, HTA, SEP, etc.)

3. **👁️ AV Brute**
   - Vision sans correction (VL & VP)
   - Pour OD, OG et Binoculaire

4. **📋 Anciennes Corrections**
   - Date dernière prescription
   - Ophtalmologiste référent

5. **✅ AV Corrigée**
   - Correction appliquée et vision avec correction
   - Pour OD, OG et Binoculaire

6. **🔍 Réfraction Finale**
   - Réfraction proposée et acuités visuelles
   - Pour OD, OG et Binoculaire

7. **📝 Observations**
   - Observations cliniques
   - Conseils verres
   - Modalité de port
   - Infos cabinet

### Fonctions principales

#### 💾 Sauvegarder
- Sauvegarde l'examen en local (dans le navigateur)
- Affiche la liste des examens sauvegardés en bas
- Les données persistent même après fermeture

#### 📊 Export Excel
- Génère un fichier `.xlsx` avec tous les champs
- Téléchargement automatique
- Format : `Examen_NOM_PRENOM_DATE.xlsx`

#### 📄 Générer rapport
- Crée un compte-rendu formaté pour ophtalmologiste
- Affichage préalable avant téléchargement
- Format : `Rapport_NOM_PRENOM_DATE.txt`

#### ➕ Nouvel examen
- Réinitialise le formulaire
- Demande confirmation si données non sauvegardées

## 💡 Conseils d'utilisation

- ✅ **Sauvegardez régulièrement** pour éviter la perte de données
- ✅ **Exportez en Excel** en fin de journée pour archivage
- ✅ **Utilisez les rapports** pour transmission ophtalmologiste
- ✅ **Testez** avant utilisation en production
- ✅ **Sauvegardez vos données** (exporter Excel régulièrement)

## 🔒 Confidentialité & Sécurité

- ✅ Les données restent **100% locales** (navigateur uniquement)
- ✅ Aucun serveur, aucun cloud
- ✅ Aucun traçage ou stockage externe
- ✅ Supprimez les données en vidant le cache navigateur si nécessaire

## 🛠️ Technologies utilisées

- **React 18** (interface utilisateur)
- **Babel** (compilation JavaScript)
- **XLSX (SheetJS)** (export Excel)
- **HTML/CSS** (mise en page)
- **localStorage** (sauvegarde locale)

## 📝 Licence

Libre d'utilisation. Adaptez-la à vos besoins.

## 📞 Support & Modifications

Pour :
- ✏️ Modifier le design/couleurs
- ➕ Ajouter des champs personnalisés
- 🔗 Ajouter une synchronisation cloud
- 🌍 Déployer sur serveur

Contactez un développeur pour adapter l'application à votre cabinet.

---

**Créée pour faciliter le travail de vos équipes d'opticiens** 👁️
