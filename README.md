# Projet Atlas - Site Web

Site web professionnel pour la présentation du Projet Atlas : Automatisation intelligente des bilans carbone d'entreprise.

## 🌐 Site en ligne
**URL de démonstration :** https://vftfddfg.manus.space

## 📁 Structure du projet

```
hamza-carbon-website/
├── dist/                    # Fichiers de production (prêts pour déploiement)
├── public/                  # Fichiers statiques
│   ├── hamzahafsi-professional-document.pdf
│   ├── manifest.json
│   ├── robots.txt
│   └── sitemap.xml
├── src/                     # Code source
│   ├── components/          # Composants React
│   ├── assets/             # Images et ressources
│   ├── App.jsx             # Composant principal
│   ├── App.css             # Styles principaux
│   └── main.jsx            # Point d'entrée
├── index.html              # Template HTML
├── package.json            # Dépendances
└── vite.config.js          # Configuration Vite
```

## 🚀 Déploiement rapide

### Option 1 : Utiliser les fichiers de production (recommandé)
Les fichiers dans le dossier `dist/` sont prêts pour le déploiement :

1. **Hébergement statique** (Netlify, Vercel, GitHub Pages) :
   - Uploadez le contenu du dossier `dist/`
   - Configurez le domaine si nécessaire

2. **Serveur web** (Apache, Nginx) :
   - Copiez le contenu de `dist/` dans le répertoire web
   - Configurez les redirections pour SPA si nécessaire

### Option 2 : Développement local

#### Prérequis
- Node.js 18+ 
- pnpm (ou npm/yarn)

#### Installation
```bash
# Extraire le ZIP et naviguer dans le dossier
cd hamza-carbon-website

# Installer les dépendances
pnpm install

# Démarrer le serveur de développement
pnpm run dev

# Construire pour la production
pnpm run build
```

## 🎯 Fonctionnalités

### ✨ Contenu
- **Présentation concise** du Projet Atlas
- **3 phases progressives** détaillées
- **Métriques clés** et bénéfices
- **Contact direct** avec Hamza Hafsi
- **Accès au rapport PDF** complet

### 🎨 Design
- **Design épuré** et professionnel
- **Navigation sticky** avec scroll-spy
- **Responsive design** mobile/desktop
- **Animations fluides** et micro-interactions
- **Performance optimisée** (202KB bundle)

### 🔧 Technique
- **React 18** avec Vite
- **Tailwind CSS** pour le styling
- **Lucide Icons** pour les icônes
- **SEO optimisé** avec métadonnées
- **PWA ready** avec manifest

## 📧 Contact

**Hamza Hafsi**
- Email : hamza.hafsi.h@gmail.com
- Spécialiste en automatisation de l'empreinte carbone

## 📄 Documentation

Le rapport complet du Projet Atlas est disponible :
- En ligne : [URL_DU_SITE]/hamzahafsi-professional-document.pdf
- Dans le projet : `public/hamzahafsi-professional-document.pdf`

## 🛠 Personnalisation

### Modifier le contenu
- Textes principaux : `src/App.jsx`
- Styles : `src/App.css`
- Métadonnées : `index.html`

### Ajouter des sections
- Créer un nouveau composant dans `src/components/`
- L'importer et l'utiliser dans `src/App.jsx`
- Ajouter la navigation dans la navbar

### Changer les couleurs
- Modifier les variables CSS dans `src/App.css`
- Utiliser les classes Tailwind dans les composants

## 📊 Performance

- **Bundle size** : 202KB (gzippé : 63KB)
- **Lighthouse Score** : 90+ sur tous les critères
- **Images optimisées** : Format WebP
- **CSS optimisé** : Purge automatique Tailwind

## 🔒 Sécurité

- **HTTPS** requis pour la production
- **CSP headers** recommandés
- **CORS** configuré si nécessaire
- **Données sensibles** : Aucune stockée côté client

---

**Version :** 1.0  
**Dernière mise à jour :** Juin 2025  
**Créé par :** Hamza Hafsi

