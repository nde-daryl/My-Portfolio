# My-Portfolio
mon porfolio professionnel
# Portfolio — Daryl Loriant Ndé Sop · NSDL

> *Étudiant en informatique · Future Data Scientist · IUT de Douala*

---

## 📋 Présentation

Ce portfolio personnel présente mon identité, mes compétences et mes réalisations dans les domaines du **design d'interfaces**, du **développement web** et de la **data science**. Il est conçu avec une esthétique **dark luxury** — fond noir profond et accents dorés — pour refléter un profil technique rigoureux et un sens aigu de l'esthétique visuelle.

---

## 🗂️ Structure du fichier

Le portfolio est un **fichier HTML unique auto-suffisant** (`portfolio.html`). Aucune dépendance externe n'est requise — toutes les images sont embarquées en base64 directement dans le fichier.

```
portfolio.html
│
├── <nav>              Navigation fixe — liens vers chaque section
├── #home              Section Hero — identité & accroche
├── #about             À propos — photo, biographie, statistiques
├── #competences       Compétences — barres de progression + tags
├── #projets           Réalisations — projet phare + grille de projets
├── #experience        Formation — timeline chronologique
├── #vision            Vision & Objectifs — citation + 3 axes
├── #contact           Contact — email, téléphone, LinkedIn, GitHub
└── <footer>           Pied de page
```

---

## 🎨 Identité visuelle

| Élément | Valeur |
|---|---|
| **Palette principale** | `#0d0d0d` (fond) · `#c8a96e` (or) · `#f0ede8` (texte) |
| **Palette secondaire** | `#141414` · `#1a1a1a` · `#a09890` (gris) |
| **Typographie** | Playfair Display (titres) · DM Sans (corps) |
| **Style général** | Dark luxury · minimalisme éditorial |
| **Initiales** | NSDL |

---

## 📁 Sections détaillées

### Hero
Première impression : nom complet en grand, titre de spécialité, tagline et deux boutons d'appel à l'action. Animation subtile sur l'indicateur de scroll.

### À propos
Photo portrait à gauche, biographie en deux paragraphes à droite. Cadre avec coin doré décoratif. Trois statistiques clés en bas (1ère année universitaire, 3+ domaines, ∞ curiosité).

### Compétences
Deux cartes de compétences avec barres de progression :
- **Design & Interfaces** : Figma (85%), UI/UX (78%), Maquettage (80%)
- **Développement Web** : HTML/CSS (82%), Bases de données (60%), Programmation (45%)

Un bloc de tags liste les domaines d'intérêt : Data Science, SQL, Python, Machine Learning, Cybersécurité, Robotique…

### Projets
**Projet phare — Manger Bio** : plateforme e-commerce de produits alimentaires biologiques camerounais. Capture d'écran réelle intégrée.

Grille secondaire de 3 projets :
1. **Portail IUT Cameroun** — site institutionnel multi-pages des 8 IUT du pays
2. **Prototype Figma** — placeholder pour future maquette interactive
3. **Nexus Tech Store** — boutique e-commerce gaming & tech dark mode

### Formation
Timeline chronologique du parcours scolaire (du plus ancien au plus récent) :
1. Groupe Scolaire Bilingue Briquiny · Douala · *Premiers pas en informatique*
2. Collège la Conquête · Douala · *Passion structurée, découverte des bases de données*
3. IUT de Douala — 1ère année Informatique · *En cours · Spécialisation Data Science*

### Vision
Citation personnelle + 3 objectifs structurés :
- **01** — Devenir Data Scientist / Data Analyst
- **02** — Cultiver un profil polyvalent (programmation, cybersécurité, dev)
- **03** — Construire des solutions à impact réel

### Contact
Coordonnées complètes avec liens cliquables :
- ✉️ loriantdaryl@gmail.com
- 📞 +237 656 271 260
- 💼 linkedin.com/in/meliodas-sama-king-b1231840a
- 🐙 github.com/nde-daryl

---

## 🚀 Utilisation

### Ouvrir le portfolio
```bash
# Double-cliquez sur le fichier, ou :
open portfolio.html        # macOS
start portfolio.html       # Windows
xdg-open portfolio.html    # Linux
```

Aucune installation, aucun serveur, aucune dépendance. Le fichier fonctionne directement dans tout navigateur moderne.

### Mettre à jour une information
Ouvrez `portfolio.html` dans un éditeur de texte (VS Code, Notepad++, Sublime Text) et recherchez le texte à modifier avec `Ctrl+F`.

---

## 📸 Ajouter ou changer une photo

Les photos sont actuellement embarquées en base64. Pour les remplacer :

**Option simple** — Remplacez l'attribut `src` de la balise `<img>` par le chemin de votre image :
```html
<!-- Avant (base64) -->
<img src="data:image/jpeg;base64,/9j/4AAQ..." alt="Daryl Loriant Ndé Sop">

<!-- Après (fichier local) -->
<img src="ma-photo.jpg" alt="Daryl Loriant Ndé Sop">
```

> ⚠️ Si vous utilisez un chemin local, placez l'image dans le même dossier que `portfolio.html`.

---

## ➕ Ajouter un projet

Dans la section `#projets`, copiez un bloc `.project-card` existant :

```html
<div class="project-card">
  <img src="mon-projet.jpg" alt="Mon Projet">
  <!-- ou : <div class="project-placeholder-bg">Capture à venir</div> -->
  <div class="project-info">
    <div class="project-tag">HTML · CSS</div>
    <div class="project-name">Nom du Projet</div>
    <div class="project-desc">Description courte en une ligne.</div>
  </div>
</div>
```

---

## ✏️ Personnaliser les compétences

Dans la section `#competences`, chaque barre se modifie ainsi :

```html
<div class="skill-item">
  <div class="skill-header">
    <span class="skill-name">Ma Compétence</span>
    <span class="skill-pct">75%</span>   <!-- ← Changez ici -->
  </div>
  <div class="skill-bar">
    <div class="skill-bar-fill" style="width:75%"></div>  <!-- ← Et ici -->
  </div>
</div>
```

---

## 🔗 Liens rapides

| Ressource | URL |
|---|---|
| Prototype Figma | https://www.figma.com/design/oWf5EeBjavu1jwOISTW34o |
| GitHub | https://github.com/nde-daryl |
| LinkedIn | https://www.linkedin.com/in/meliodas-sama-king-b1231840a |
| Email | loriantdaryl@gmail.com |

---

## 🛠️ Technologies utilisées

- **HTML5** — Structure sémantique
- **CSS3** — Variables, Flexbox, Grid, animations, backdrop-filter
- **Google Fonts** — Playfair Display + DM Sans
- **Images** — Encodage base64 (auto-suffisant, zéro dépendance)

---

## 📄 Licence

Portfolio personnel — tous droits réservés.  
© 2025 Daryl Loriant Ndé Sop

---

*Conçu et développé par Daryl Loriant Ndé Sop · NSDL · Douala, Cameroun*
