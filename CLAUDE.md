# LDVK - Production Vidéo & Consulting Digital

## Accès

- **Site**: https://ldvk.fr
- **GitHub**: https://github.com/tfwb5wfxwq-crypto/ldvk-site
- **Email contact**: ldvk@me.com (via Formsubmit)

## Stack

- HTML/CSS/JS statique
- GitHub Pages
- Formsubmit pour le formulaire contact

## Ce qui a été fait (Session 02/02/2026)

### Logo nav "LDVK"
- Chaque lettre dans un span
- Shuffle aléatoire au hover (desktop) et tap (mobile)
- Se remet en place après 8-12 interactions (comme un jackpot)

### Effet grain
- Grain animé style pellicule cinéma
- Opacity 5%, animation 0.5s steps

### Fond
- Couleur #050505 (plus sombre que #0a0a0a)

### Tagline
- "Production Vidéo • Data" avec bullet point
- Hover: scale(1.1) + letter-spacing 0.25em
- Plus de underline

### Logos clients (en bas, statiques)
- Winamax, La Poste, Webedia, Macif, France TV, Terry's, Court ou Crève, Prime Video, Freaks
- Filtre: grayscale(1) invert(1) brightness(1.5)
- Tailles ajustées par logo (Terry's 28px, Freaks 20px, COC 50px, autres 38px)

### Modal Contact
- Titre: "On discute ?"
- Formulaire: Nom, Email, Message
- Validation custom (shake + bordure rose, pas d'alerte browser)
- Animation success: checkmark gradient violet/rose avec glow pulsé
- Auto-ferme après 3 secondes
- Reset du formulaire automatique
- Envoi via Formsubmit à ldvk@me.com

### Modals général
- Croix en haut à droite (position fixed)
- Effet hover: rotation + gradient multicolore

## Fichiers clés

- `index.html` - tout le site (single page)
- `logos/` - dossier avec les logos clients PNG/SVG
- `og-image.png` - image pour partage social
