# Pages publiques de Dafter

Politique de confidentialité, conditions d'utilisation et page de suppression de compte.
Google Play demande les liens vers la confidentialité et la suppression de compte.

## Publier gratuitement avec GitHub Pages (10 minutes)

1. Créez un compte sur github.com si besoin, puis un dépôt **public** nommé `dafter`.
2. Mettez-y les fichiers de ce dossier (bouton **Add file → Upload files**).
3. Allez dans **Settings → Pages** → Source : *Deploy from a branch*, branche `main`, dossier `/ (root)` → **Save**.
4. Une minute plus tard, le site est en ligne sur `https://VOTRE-COMPTE.github.io/dafter/`.
5. Dans l'app, mettez cette adresse dans `lib/core/liens.dart` (ligne `site = ...`).

Dans la Play Console, indiquez :
- Politique de confidentialité : `https://VOTRE-COMPTE.github.io/dafter/confidentialite.html`
- Suppression du compte : `https://VOTRE-COMPTE.github.io/dafter/suppression-compte.html`
