# Loulou Fitness – site vitrine

Site statique (HTML/CSS, sans JavaScript ni cookies). La réservation et le paiement restent sur l’appli existante.

## À compléter avant la mise en ligne
1. **Adresse de l’appli** : remplacer `https://reservation.loulou-fitness.fr` dans `index.html` (recherche/remplacement global).
2. **Photos** : ajouter `assets/hero.webp`, `assets/coach.webp`, `assets/og.jpg` (1200×630), puis remplacer les blocs « Photo » par les balises `<img>` indiquées en commentaire (avec un texte `alt`).
3. **Adresse exacte du studio** dans le pied de page (et, si souhaité, dans le balisage JSON-LD).
4. **Témoignages** : remplir la section `#avis` et retirer l’attribut `hidden`.
5. **Mentions légales** : compléter `mentions-legales.html` (nom, SIRET, hébergeur). Ajouter aussi CGV et politique de confidentialité.
6. Vérifier les horaires (le samedi notamment).

## Tester en local
`python3 -m http.server 8000` puis ouvrir http://localhost:8000

## Déployer (gratuit)
Cloudflare Pages, Netlify ou GitHub Pages : connecter le dépôt, **pas de commande de build**, dossier de publication = racine. Puis ajouter le domaine `loulou-fitness.fr` (la bascule DNS se fait en dernier, après avoir déplacé l’appli sur son sous-domaine).

## Après la mise en ligne
Ajouter le site dans Google Search Console, envoyer `sitemap.xml`, créer la fiche Google Business Profile.
