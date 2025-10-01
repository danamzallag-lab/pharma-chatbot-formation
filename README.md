# 🤖 PharmaBot AI - Formation Pharmaceutique Intelligente

Site web de chatbot de formation pharmaceutique avec assistant IA intégré.

## 📋 Description

PharmaBot AI est un assistant intelligent dédié à la formation continue des pharmaciens. Il fournit des réponses instantanées et précises sur les nouvelles missions pharmaceutiques, basées sur les supports de formation officiels.

## ✨ Fonctionnalités

- 💬 Assistant IA conversationnel (n8n chat)
- 🎯 Spécialisé dans la formation pharmaceutique
- 🌓 Mode clair/sombre
- 📱 Design responsive
- ✨ Animations et effets visuels modernes
- 🔒 Sécurisé et confidentiel

## 🚀 Déploiement sur Vercel

### 1. Initialiser le dépôt Git

```bash
cd pharma-chatbot-formation
git init
git add .
git commit -m "Initial commit: PharmaBot AI"
```

### 2. Pousser sur GitHub

```bash
git branch -M main
git remote add origin <votre-url-github>
git push -u origin main
```

### 3. Déployer sur Vercel

1. Connectez-vous à [Vercel](https://vercel.com)
2. Cliquez sur "New Project"
3. Importez votre dépôt GitHub
4. Vercel détectera automatiquement la configuration
5. Cliquez sur "Deploy"

## 📁 Structure du Projet

```
pharma-chatbot-formation/
├── index.html          # Page principale
├── vercel.json         # Configuration Vercel
├── package.json        # Métadonnées du projet
├── .gitignore          # Fichiers à ignorer par Git
└── README.md           # Ce fichier
```

## 🛠️ Technologies Utilisées

- HTML5
- CSS3 (animations, glassmorphism)
- JavaScript (ES6+)
- n8n Chat Widget
- Vercel (hébergement)

## 🔧 Configuration

Le chatbot utilise l'URL webhook n8n configurée dans le code. Pour modifier l'URL :

1. Ouvrez `index.html`
2. Recherchez `webhookUrl`
3. Remplacez par votre URL webhook n8n

## 📝 Licence

© 2025 PharmaBot AI - Développé par Innovapharm Consulting

## 👨‍💻 Développement

Développé avec ❤️ par Innovapharm Consulting pour les pharmaciens.
