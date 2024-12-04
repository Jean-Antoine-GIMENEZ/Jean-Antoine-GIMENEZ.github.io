<style>
  .menu {
    position: fixed;
    top: 0;
    left: 0;
    width: 200px;
    height: 100%;
    background-color: #f4f4f4;
    padding: 10px;
    box-shadow: 2px 0px 5px rgba(0, 0, 0, 0.1);
  }

  .content {
    margin-left: 220px;
    padding: 10px;
  }

  .menu ul {
    list-style-type: none;
    padding: 0;
  }

  .menu ul li {
    margin: 10px 0;
  }

  .menu ul li a {
    text-decoration: none;
    color: #007bff;
  }

  .menu ul li a:hover {
    text-decoration: underline;
  }
</style>

<div class="menu">
  <h2>Menu</h2>
  <ul>
    <li><a href="#présentation">Présentation</a></li>
    <li><a href="#structure">Structure</a></li>
    <ul>
      <li><a href="#portfolio">Portfolio</a></li>
      <li><a href="#page">Page</a></li>
      <li><a href="#projet">Projet</a></li>
      <li><a href="#cv">CV</a></li>
      <li><a href="#badge">Badge</a></li>
    </ul>
    <li><a href="#détails-des-classes">Détails des Classes</a></li>
    <ul>
      <li><a href="#classe-portfolio">Classe Portfolio</a></li>
      <li><a href="#classe-page">Classe Page</a></li>
      <li><a href="#classe-projet">Classe Projet</a></li>
      <li><a href="#classe-cv">Classe CV</a></li>
      <li><a href="#classe-badge">Classe Badge</a></li>
    </ul>
  </ul>
</div>

<div class="content">
  # Portfolio

  Bienvenue dans la documentation du portfolio.

  ## Présentation

  Ce document détaille la structure d'un portfolio en utilisant un diagramme basé sur Mermaid.

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

  ## Détails des Classes

  ### Classe Portfolio

  Attributs :
  - `+String titre`
  - `+String description`
  - `+String theme`

  ### Classe Page

  Attributs :
  - `+String nom`
  - `+String contenu`

  ### Classe Projet

  Attributs :
  - `+String nom`
  - `+String description`
  - `+String url`

  ### Classe CV

  Attributs :
  - `+String fichier`

  ### Classe Badge

  Attributs :
  - `+String fichier`
</div>
