<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        /* Style général de la page */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
        }

        /* Menu à gauche */
        .menu {
            position: fixed;
            top: 0;
            left: 0;
            width: 200px;
            height: 100%;
            background-color: #f4f4f4;
            padding: 20px;
            box-shadow: 2px 0px 5px rgba(0, 0, 0, 0.1);
        }

        .menu h2 {
            text-align: center;
            color: #333;
        }

        .menu ul {
            list-style-type: none;
            padding: 0;
        }

        .menu ul li {
            margin: 15px 0;
        }

        .menu ul li a {
            text-decoration: none;
            color: #007bff;
            font-size: 16px;
        }

        .menu ul li a:hover {
            text-decoration: underline;
        }

        /* Contenu principal */
        .content {
            margin-left: 220px;
            padding: 20px;
            flex-grow: 1;
        }

        /* Styles pour les sections */
        h1, h2, h3 {
            color: #333;
        }

        p {
            font-size: 1rem;
            color: #555;
        }

        /* Séparateurs horizontaux */
        hr {
            border: 1px solid #ddd;
        }
    </style>
</head>
<body>

    <!-- Menu de navigation à gauche -->
    <div class="menu">
        <h2>Menu</h2>
        <ul>
            <li><a href="#présentation">Présentation</a></li>
            <li><a href="#structure">Structure</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#page">Page</a></li>
            <li><a href="#projet">Projet</a></li>
            <li><a href="#cv">CV</a></li>
            <li><a href="#badge">Badge</a></li>
        </ul>
    </div>

    <!-- Contenu principal -->
    <div class="content">
        <h1>Portfolio</h1>
        <p>Bienvenue dans la documentation du portfolio.</p>

        ## Présentation

        Ce document détaille la structure d'un portfolio en utilisant un diagramme basé sur Mermaid.

        <hr>

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

        #### Informations Personnelles

        - **Email** : [jean-antoine.gimenez@etudiant.univ-perp.fr](mailto:jean-antoine.gimenez@etudiant.univ-perp.fr)
        - **Téléphone** :
        - **Adresse** :
        - **Mobilité** : Aude
        - **Âge** : 20 ans
        - **Permis** : A2, B
        - **Véhicule personnel**

        <hr>

        #### Compétences

        ##### Base de données
        - Extraction, nettoyage et gestion de BDD
        - Requêtes SQL et création de tableaux de bord
        - Automatisation de collecte de données sous BDD

        ##### Statistique
        - Conduite d’études statistiques
        - Analyse et communication des résultats
        - Conception de questionnaires

        ##### Programmation
        - **Langages** : Python, SQL/PLSQL, R, SAS, HTML/CSS, JavaScript, PHP, SVG
        - **Logiciels** : Sphinx, Microsoft Office (Excel, Access, PowerPoint, Power BI), ArcGIS, QGIS, FME, pgAdmin

        <hr>

        #### Formations

        - **BUT Science des Données (SD)**  
          *Université de Perpignan, depuis septembre 2022*

        #### Expériences et Projets
        - **Création d'une application web GPS** *(Octobre 2023 à janvier 2024 - IUT Carcassonne)*  
          - Application web avec gestion de compte personnel  
          - Visualisation cartographique (SIG), itinéraires, et points de repère
          
        #### Langues
        - **Anglais** : B2  
        - **Espagnol** : B1

        #### Centres d'Intérêt
        - **Caisse à savon** : Construction et course de véhicules sans moteur

        <hr>

        *Site web basé sur un thème Hacker.*

        <hr>

        ## Badge

        Une section pour les fichiers associés aux certifications et badges.
    </div>

</body>
</html>
