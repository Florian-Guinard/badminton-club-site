# 🏸 Badminton Club — site vitrine

Base de site responsive pour une association de badminton.

## Structure

- `index.html` — accueil
- `club.html` — présentation du club
- `creneaux.html` — horaires
- `equipes.html` — équipes
- `photos.html` — galerie
- `actualites.html` — actualités
- `contact.html` — contact / inscription
- `assets/css/style.css` — design et responsive
- `assets/js/main.js` — menu mobile
- `assets/images/` — vos photos

## Personnalisation rapide

Les couleurs principales sont tout en haut de `assets/css/style.css` :

```css
--navy:#061936;
--lime:#c7f23a;
--white:#fff;
```

Modifiez ces valeurs pour changer l'identité visuelle du site.

Les horaires, textes, noms d'équipes et coordonnées sont directement dans les fichiers HTML.

## Ajouter une vraie photo

Placez une image dans `assets/images/`, par exemple :

`hero.jpg`

Puis la section hero utilisera automatiquement cette image.

Pour les autres photos, remplacez les blocs `.image-placeholder` par des balises `<img>`.

## Mise en ligne

Ce site ne nécessite ni PHP ni base de données.

Il peut être publié gratuitement avec GitHub Pages, Cloudflare Pages ou Netlify.

## Important

Le formulaire de contact est uniquement visuel dans cette base. Pour recevoir réellement les messages, connectez-le à un service comme Google Forms, Formspree ou une solution équivalente.
