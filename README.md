# Levio landing

Landing page statique pour **Levio** (alarme intelligente avec missions).

## Développement local

```bash
npm install
npm start
```

Ou sans installation : `npx serve .` à la racine du projet.

## Déploiement sur Vercel

1. Pousser ce dossier sur un dépôt Git (GitHub, GitLab, etc.).
2. Sur [vercel.com](https://vercel.com), **Add New Project** → importer le dépôt.
3. Laisser les réglages par défaut (projet statique, racine du repo si le site est à la racine).
4. Déployer. Vercel utilisera `vercel.json` pour les en-têtes et le routage.

### Assets

Remplacez `assets/icon.png` et `assets/og-image.png` par vos fichiers finaux (logo et visuel Open Graph). Mettez à jour l’URL canonique et les meta `og:*` / `twitter:*` dans `index.html` si votre domaine n’est pas `https://levio.app`.
