# App Landing — GitHub Pages

Site statique minimal pour présenter une app iOS (1 page). Déploiement gratuit via **GitHub Pages**.

## Déploiement (en 3 minutes)
1. Crée un dépôt GitHub (public) et upload les fichiers de ce dossier à la racine.
2. Dans le dépôt : **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `/root`**.
3. Ouvre l’URL indiquée par GitHub Pages (du type `https://ton-utilisateur.github.io/nom-du-depot`).
4. Remplace dans `index.html` :
   - `YOUR_APP_ID` par l’ID réel de l’app (meta smart banner iOS).
   - Les URLs `apps.apple.com/...`.
   - Le `og:image` par un vrai visuel (ou supprime la meta).
5. (Optionnel) Ajoute un domaine custom via **Settings → Pages → Custom domain**.

## Personnalisation
- Couleurs & typographie : `styles.css`
- Logo : `assets/logo.svg`
- Mockup iPhone : `assets/iphone-mock.svg`
- Favicon : `assets/favicon.svg`
- Politique de confidentialité : `privacy.html`

## Badge App Store
Par défaut, le bouton “Download on the App Store” est un bouton CSS **temporaire**.
Remplace-le par le **badge officiel Apple** (SVG) conformément aux guidelines Apple et lie-le à ton URL App Store.

