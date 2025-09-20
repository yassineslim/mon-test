# mon-test
# InstaMock - Landing Page

Une landing page moderne inspirée d'Instagram, construite avec **React** et **Tailwind CSS**.

## 🚀 Démo

Vous pouvez prévisualiser le site en local ou le déployer sur **GitHub Pages**.

## 📦 Installation

1. **Cloner le dépôt**

```bash
git clone https://github.com/votre-utilisateur/instamock-landing.git
cd instamock-landing
```

2. **Installer les dépendances**

```bash
npm install
```

3. **Lancer en développement**

```bash
npm run dev
```

Puis ouvrez [http://localhost:5173](http://localhost:5173) dans votre navigateur.

## 🛠 Stack utilisée

- [React](https://react.dev/) — Interface utilisateur
- [Vite](https://vitejs.dev/) — Build rapide
- [Tailwind CSS](https://tailwindcss.com/) — Style

## 🌐 Déploiement sur GitHub Pages

1. Ajoutez le package `gh-pages`

```bash
npm install --save-dev gh-pages
```

2. Ajoutez dans `package.json` :

```json
"homepage": "https://votre-utilisateur.github.io/instamock-landing",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist"
}
```

3. Déployez :

```bash
npm run deploy
```

## ✨ Personnalisation

- Modifiez **src/InstagramLanding.jsx** pour changer le contenu, les couleurs et les images.
- Remplacez les URLs par vos propres captures d’écran ou assets.

## 📄 Licence

MIT — libre d'utilisation et de modification.

