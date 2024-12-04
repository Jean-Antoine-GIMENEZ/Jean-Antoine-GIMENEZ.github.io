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
  <h1>Portfolio</h1>

  <p>Bienvenue dans la documentation du portfolio.</p>

  <h2 id="présentation">Présentation</h2>
  <p>Ce document détaille la structure d'un portfolio en utilisant un diagramme basé sur Mermaid.</p>

  <h2 id="structure">Structure</h2>

  <h3 id="portfolio">Portfolio</h3>
  <p>Le <strong>Portfolio</strong> contient :</p>
  <ul>
    <li><a href="#page">Page</a></li>
    <li><a href="#projet">Projet</a></li>
    <li><a href="#cv">CV</a></li>
    <li><a href="#badge">Badge</a></li>
  </ul>

  <h3 id="page">Page</h3>
  <p>Une page du portfolio, contenant des informations spécifiques.</p>

  <h3 id="projet">Projet</h3>
  <p>Une section dédiée aux projets, incluant description et lien.</p>

  <h3 id="cv">CV</h3>

  <h4>Informations Personnelles</h4>
  <ul>
    <li><strong>Email</strong> : <a href="mailto:jean-antoine.gimenez@etudiant.univ-perp.fr">jean-antoine.gimenez@etudiant.univ-perp.fr</a></li>
    <li><strong>Téléphone</strong> : </li>
    <li><strong>Adresse</strong> : </li>
    <li><strong>Mobilité</strong> : Aude</li>
    <li><strong>Âge</strong> : 20 ans</li>
    <li><strong>Permis</strong> : A2, B</li>
    <li><strong>Véhicule personnel</strong></li>
  </ul>

  <h4>Compétences</h4>
  <h5>Base de données</h5>
  <ul>
    <li>Extraction, nettoyage et gestion de BDD</li>
    <li>Requêtes SQL et création de tableaux de bord</li>
    <li>Automatisation de collecte de données sous BDD</li>
  </ul>
  <h5>Statistique</h5>
  <ul>
    <li>Conduite d’études statistiques</li>
    <li>Analyse et communication des résultats</li>
    <li>Conception de questionnaires</li>
  </ul>
  <h5>Programmation</h5>
  <ul>
    <li><strong>Langages</strong> : Python, SQL/PLSQL, R, SAS, HTML/CSS, JavaScript, PHP, SVG</li>
    <li><strong>Logiciels</strong> : Sphinx, Microsoft Office (Excel, Access, PowerPoint, Power BI), ArcGIS, QGIS, FME, pgAdmin</li>
  </ul>

  <h4>Formations</h4>
  <ul>
    <li><strong>BUT Science des Données (SD)</strong>  
      <em>Université de Perpignan, depuis septembre 2022</em>
    </li>
    <li><strong>Baccalauréat général</strong>  
      <em>Lycée Ernest Ferroul, 2022</em>  
      Mention Bien | Mathématiques, Numérique Science Informatique, Mathématiques expertes
    </li>
  </ul>

  <h4>Expériences et Projets</h4>
  <h5>Mise en place d'un Service SIG</h5>
  <em>Stage + CDD | Avril 2024 à août 2024 - Communauté des Communes La Domitienne (Vendres)</em>
  <ul>
    <li>Diagnostic des données internes et externes</li>
    <li>Analyse des besoins métiers</li>
    <li>Recherche d’exemples d’organisation similaires</li>
  </ul>

  <h5>Création d'une application web GPS</h5>
  <em>Octobre 2023 à janvier 2024 - IUT Carcassonne</em>
  <ul>
    <li>Application web avec gestion de compte personnel</li>
    <li>Visualisation cartographique (SIG), itinéraires, et points de repère</li>
    <li><strong>Technologies</strong> : MySQL, PHP, JavaScript</li>
  </ul>

  <h5>Mise en œuvre d'une enquête</h5>
  <em>Octobre 2022 à janvier 2023 - Carcassonne Agglo</em>
  <ul>
    <li>Élaboration d’un questionnaire et saisie des réponses</li>
    <li>Analyse statistique (Sphinx) et rédaction de rapport</li>
    <li>Préconisations au commanditaire</li>
  </ul>

  <h4>Langues</h4>
  <ul>
    <li><strong>Anglais</strong> : B2</li>
    <li><strong>Espagnol</strong> : B1</li>
  </ul>

  <h4>Centres d'Intérêt</h4>
  <ul>
    <li><strong>Caisse à savon</strong> : Construction et course de véhicules sans moteur</li>
    <li><strong>Moto</strong></li>
    <li><strong>Électronique/Informatique</strong> : Objets connectés, analyse statistique, SIG</li>
    <li><strong>Histoire</strong> : XIXe et XXe siècles</li>
  </ul>

  <h3 id="badge">Badge</h3>
  <p>Une section pour les fichiers associés aux certifications et badges.</p>
</div>
