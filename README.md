# Forceux Académie — Programme Powerlifting 9 semaines

Application web statique pour suivre ton programme d'entraînement.

## 🚀 Déploiement sur GitHub Pages

### 1. Créer un nouveau repo GitHub
- Va sur github.com → "New repository"
- Nomme-le `forceux-academie` (ou ce que tu veux)
- Laisse-le **public** (requis pour GitHub Pages gratuit)

### 2. Pousser le code
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TON_USERNAME/forceux-academie.git
git push -u origin main
```

### 3. Activer GitHub Pages
- Va dans ton repo → **Settings** → **Pages**
- Source : **GitHub Actions**
- Le déploiement se lance automatiquement !

### 4. Accéder à l'app
Ton app sera disponible sur :
`https://TON_USERNAME.github.io/forceux-academie/`

## 💾 Persistance des données
Toutes les données (log, 1RM, configuration du planning) sont sauvegardées dans le **localStorage** du navigateur. Elles persistent entre les sessions sur le même appareil/navigateur.

## 📁 Structure
```
index.html     ← Application complète (tout-en-un)
README.md
.github/
  workflows/
    deploy.yml ← Déploiement automatique sur GitHub Pages
```
