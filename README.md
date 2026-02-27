# ⏱ Générateur de Frise Chronologique

> Créez des frises chronologiques interactives embarquables sur n'importe quel blog ou site — gratuit, prêt à coller

[![Live](https://img.shields.io/badge/LIVE-Essayer_l'outil-c8ff00?style=flat-square&labelColor=0a0a0a)](https://levaisseaumonde.github.io/timeline-generator/)
[![BlackCrow](https://img.shields.io/badge/BlackCrow_OS-Hub-333?style=flat-square&labelColor=0a0a0a)](https://levaisseaumonde.github.io/BlackCrow/)

---

## Fonctionnalités

- Créer une frise chronologique interactive avec points cliquables, images et liens
- Personnaliser couleurs (fond, frise, texte, carte de survol), police et tailles de texte
- Carte de détail au survol : s'ouvre latéralement depuis la miniature avec effet zoom
- Chaque point peut pointer vers une URL (YouTube, article, Wattpad…)
- Images encodées en base64 dans le navigateur — aucun hébergement externe requis
- Bouton de téléchargement PNG intégré dans le widget généré
- Branding double (vaisseau-monde.fr / BlackCrow OS) activable indépendamment
- Sauvegarde automatique dans le localStorage — reprendre là où on en était
- Prévisualisation en temps réel
- Générer le code HTML/JS/CSS prêt à copier-coller
- Aucune dépendance externe — le widget généré est entièrement autonome

---

## Utilisation

1. Ouvrir [l'outil](https://levaisseaumonde.github.io/timeline-generator/)
2. Configurer le titre, l'unité de temps, les couleurs et la typographie
3. Ajouter des points : date, légende, description, image, lien URL
4. Prévisualiser ou générer le widget
5. Copier le code HTML ou télécharger le fichier `.html`
6. Coller dans un gadget HTML/JavaScript de Blogger, WordPress, ou tout autre site

Aucun compte requis. Aucune pub. Aucun serveur.

---

## Intégration BlackCrow OS

Cet outil fait partie de la suite [BlackCrow OS](https://levaisseaumonde.github.io/BlackCrow/), l'interface système de l'univers [Le Vaisseau-Monde](https://www.vaisseau-monde.fr).

La navbar est chargée dynamiquement depuis le hub central :

```html
<div id="bc-navbar"></div>
<script>
  fetch('https://levaisseaumonde.github.io/BlackCrow/navbar.html')
    .then(r => r.text())
    .then(html => document.getElementById('bc-navbar').innerHTML = html);
</script>
```

---

## Liens

- 🌐 [vaisseau-monde.fr](https://www.vaisseau-monde.fr)
- 📺 [YouTube @VaisseauMonde](https://www.youtube.com/@VaisseauMonde)
- 📖 [Wattpad — Le Vaisseau-Monde](https://www.wattpad.com/story/407419657-le-vaisseau-monde)
- 🔗 [BlackCrow OS](https://levaisseaumonde.github.io/BlackCrow/)

---

*QLVVP 🖤*
