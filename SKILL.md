---
name: frontend-design
description: "Creation d'interfaces frontend distinctives et de qualite production (composants web, pages, landing pages, dashboards, applications React/HTML/CSS). Utiliser quand l'utilisateur demande de construire une interface web, un composant UI, une page, une application, ou quand il veut embellir/styler un frontend existant. Genere du code fonctionnel avec une direction esthetique forte et intentionnelle, en evitant les cliches visuels generiques."
---

# Frontend Design

Créer des interfaces frontend distinctives, production-grade, avec une direction esthétique forte. Implémenter du code fonctionnel avec une attention méticuleuse aux détails visuels.

---

## DESIGN THINKING — Avant de coder

Comprendre le contexte et s'engager sur une direction esthétique **BOLD** :

- **Objectif** : Quel problème cette interface résout-elle ? Qui l'utilise ?
- **Ton** : Choisir un extrême et l'assumer — brutalisme minimaliste, chaos maximaliste, rétro-futuriste, organique/naturel, luxe/raffiné, jouet/playful, éditorial/magazine, brutalist/raw, Art Déco/géométrique, pastel/doux, industriel/utilitaire, etc.
- **Contraintes** : Framework requis, performance, accessibilité.
- **Différenciation** : Qu'est-ce qui rend cette interface **INOUBLIABLE** ? Quelle est la chose qu'on retiendra ?

**CRITIQUE** : Choisir une direction conceptuelle claire et l'exécuter avec précision. Le maximalisme assumé et le minimalisme raffiné fonctionnent tous les deux — ce qui compte, c'est l'intentionnalité, pas l'intensité.

---

## STANDARDS ESTHÉTIQUES

### Typographie
Choisir des polices belles, uniques et caractérielles. **Éviter absolument** : Arial, Inter, Roboto, system fonts. Préférer des choix inattendus qui élèvent l'esthétique. Associer une police display distinctive avec une police body raffinée. Charger via Google Fonts ou CDN selon le contexte.

### Couleur & Thème
S'engager sur une esthétique cohérente. Utiliser des variables CSS pour la consistance. Une couleur dominante avec des accents tranchants surpasse toujours une palette timide et équilibrée.

### Motion & Animations
Utiliser les animations pour les effets et micro-interactions. Privilégier les solutions CSS-only pour HTML pur. Utiliser la librairie Motion pour React quand disponible. Se concentrer sur les moments à fort impact : un chargement de page bien orchestré avec des révélations décalées (`animation-delay`) crée plus de plaisir que des micro-interactions dispersées. Exploiter le scroll-triggering et les hover states surprenants.

### Composition Spatiale
Layouts inattendus. Asymétrie. Chevauchements. Flux diagonal. Éléments qui cassent la grille. Espace négatif généreux OU densité contrôlée.

### Arrière-plans & Détails Visuels
Créer de l'atmosphère et de la profondeur plutôt que des couleurs unies. Effets contextuels et textures qui correspondent à l'esthétique globale : gradient meshes, textures noise, motifs géométriques, transparences superposées, ombres dramatiques, bordures décoratives, curseurs custom, overlays grain.

---

## CE QU'IL FAUT ÉVITER ABSOLUMENT

- Polices sur-utilisées : Inter, Roboto, Arial, Space Grotesk, system fonts
- Schémas de couleurs éculés : dégradés violets sur fond blanc, bleu corporate générique
- Layouts et patterns de composants prévisibles et cookie-cutter
- Design sans caractère spécifique au contexte

Interpréter créativement. Aucun design ne doit ressembler à un autre. Varier entre thèmes clairs et sombres, polices différentes, esthétiques différentes. **Ne jamais converger sur les mêmes choix** d'une génération à l'autre.

---

## IMPLÉMENTATION

Le code produit doit être :
- **Production-grade et fonctionnel** — pas un prototype approximatif
- **Visuellement frappant et mémorable** — direction esthétique assumée
- **Cohérent** — point de vue esthétique clair du début à la fin
- **Méticuleusement raffiné** dans chaque détail

Adapter la complexité d'implémentation à la vision esthétique : les designs maximalistes nécessitent un code élaboré avec animations et effets extensifs. Les designs minimalistes nécessitent de la retenue, de la précision, et une attention soignée à l'espacement, la typographie, et les détails subtils.

**Pour les projets web complets** (landing pages, applications multi-pages), utiliser l'outil `webdev_init_project` pour scaffolder l'environnement (Vite + React + TypeScript + TailwindCSS) avant de coder, puis exposer une URL de prévisualisation via l'outil `expose`.

**Pour les composants ou pages autonomes**, produire un fichier `.html` auto-contenu avec CSS et JS inline ou via CDN.

---

## LIVRAISON

Livrer le code complet et fonctionnel avec une URL de prévisualisation quand possible. Toujours inclure une capture d'écran ou décrire les choix esthétiques clés effectués (palette, typographie, direction de design).
