# Portfolio

Bienvenue dans la documentation du portfolio.

## Menu

- [Présentation](#présentation)
- [Structure](#structure)
  - [Portfolio](#portfolio)
  - [Page](#page)
  - [Projet](#projet)
  - [CV](#cv)
  - [Badge](#badge)
- [Détails des Classes](#détails-des-classes)
  - [Classe Portfolio](#classe-portfolio)
  - [Classe Page](#classe-page)
  - [Classe Projet](#classe-projet)
  - [Classe CV](#classe-cv)
  - [Classe Badge](#classe-badge)

---

## Présentation

Ce document détaille la structure d'un portfolio en utilisant un diagramme basé sur Mermaid.

---

## Structure

### Portfolio

Le **Portfolio** contient :
- [Page](#page)
- [Projet](#projet)
- [CV](#cv)
- [Badge](#badge)

### Page

Une page du portfolio, contenant des informations spécifiques.

### Projet

Une section dédiée aux projets, incluant description et lien.

### CV

Un espace pour ajouter un fichier de curriculum vitae.

### Badge

Une section pour les fichiers associés aux certifications et badges.

---

## Détails des Classes

### Classe Portfolio

Attributs :
- `+String titre`
- `+String description`
- `+String theme`

Associations :
- Contient : [Page](#classe-page), [Projet](#classe-projet), [CV](#classe-cv), [Badge](#classe-badge)

---

### Classe Page

Attributs :
- `+String nom`
- `+String contenu`

---

### Classe Projet

Attributs :
- `+String nom`
- `+String description`
- `+String url`

---

### Classe CV

Attributs :
- `+String fichier`

---

### Classe Badge

Attributs :
- `+String fichier`
