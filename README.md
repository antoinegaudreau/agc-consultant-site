# Site web — AGC Consultant inc.

Site vitrine statique (HTML/CSS/JS, sans dépendances ni étape de compilation).

**Domaine :** agcconsultant.ca
**Hébergement :** Cloudflare Pages

## Déploiement

Ce dépôt se déploie tel quel sur Cloudflare Pages :

- Commande de build : *(laisser vide)*
- Dossier de sortie : `/` (racine)

Chaque `push` sur la branche principale redéploie automatiquement le site.

## Structure

| Fichier | Rôle |
|---|---|
| `index.html` | Page d'accueil |
| `genie-agricole.html` | Expertise — Génie |
| `agronomie.html` | Expertise — Agronomie |
| `environnement.html` | Expertise — Environnement |
| `apropos.html` | À propos |
| `blog.html` | Index du blogue |
| `article-*.html` | Articles de veille réglementaire |
| `portail.html` | Portail client (en développement) |
| `404.html` | Page d'erreur |
| `sitemap.xml` / `robots.txt` | Référencement |
| `photo-*.jpg`, `logo-*.png` | Images du site |
| `og-*.jpg` | Cartes de partage (réseaux sociaux) |
| `hero.mp4`, `hero-poster.jpg` | Vidéo d'en-tête |

## Notes

- Le formulaire de contact utilise Web3Forms (clé d'accès dans `index.html`).
- Analytique : le script Cloudflare Web Analytics est présent en commentaire dans chaque page, prêt à activer avec le token.
- Toutes les pages sont autonomes : aucune dépendance externe sauf les polices Google Fonts.
