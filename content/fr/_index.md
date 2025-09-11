---
title: 'Acceuil'
date: 2024-11-11
type: landing

design:
  # Default section spacing
  spacing: "rem"

sections:
  - block: hero
    content:
      title: La plateforme MEDomics
      text:  Modélisation intégrative de données hétérogènes en médecine
      primary_action:
        text: Commencer
        url: https://medomics-udes.gitbook.io/medomicslab-docs/
        icon: rocket-launch
      secondary_action:
        text: Explorer les tutoriels
        url: https://youtube.com/@MEDomicsLab
      announcement:
        text: La première version est
        link:
          text: là!
          url: /fr/#download
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: medical-ai.png
          filters:
            brightness: 0.4
    
  - block: markdown
    id: youtube
    id: overview
    content:
      title: Découvrez la plateforme MEDomics
      text: |
        <div style="text-align: center;">
          <iframe width="1280" height="720" src="https://www.youtube.com/embed/2daEWBb_SNo?si=0ROdUzS6PSWiUQWm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>

  - block: features
    id: dashboard
    content:
      title: Tout dans une seule interface
      text: À un clic de votre premier modèle prédictif
      items:
        - name: Gestion facile
          icon: sparkles
          description: La plateforme MEDomics simplifie la gestion de divers ensembles de données et ressources, offrant une vue organisée et unifiée des données médicales. Grâce à son interface intuitive, les chercheurs peuvent facilement traiter des données complexes sans obstacles techniques, simplifiant ainsi l'analyse. 
        - name: Gagnez du temps
          icon: clock
          description: Dotée de tous les outils essentiels, la plateforme MEDomics permet aux utilisateurs de gagner du temps en permettant la configuration d'expériences sans aucun codage. Des pipelines intégrés et des workflows personnalisables permettent aux utilisateurs de passer rapidement des données aux informations, améliorant ainsi leur efficacité et leur permettant de se concentrer sur la recherche.
        - name: Favoriser la synergie
          icon: users
          description: Conçu pour la collaboration, la plateforme MEDomics comble le fossé entre cliniciens et informaticiens. Les cliniciens peuvent concevoir des expériences, tandis que les informaticiens les peaufinent et les adaptent, favorisant ainsi le travail d'équipe pour le développement de modèles prédictifs performants.

  - block: markdown
    id: highlights
    content:
      title: Points forts
      text: |
        <style>
        .highlights {
          text-align: center;
          width: 1800px;
        }

        .highlights-content {
          display: flex;
          justify-content: center;
          align-items: center;
        }

        .highlights-column-left {
          width: 25%;
          padding: 1rem;
          text-align: left;
        }

        .highlights-column-right {
          width: 25%;
          padding: 1rem;
          text-align: right;
        }

        .highlights-image img {
          width: 400px; /* Adjust as needed */
          margin: 1rem;
          display: block;
        }

        .highlight-item h3 {
          font-weight: bold;
          font-size: 1.2em;
          margin: 1.5rem 0;
        }
        </style>
        <section class="highlights">
        <h1>Les principales fonctionnalités de la plateforme MEDomics</h1>
         <div class="highlights-content">
          <!-- Left Column -->
          <div class="highlights-column-right">
            <div class="highlight-item">
              <h3>Tableau de bord unifié</h3>
              <p>Un hub central où les utilisateurs peuvent gérer des ensembles de données, former des modèles prédictifs et exécuter diverses expériences sans basculer entre les outils.</p>
            </div>
            <div class="highlight-item">
              <h3>Conception d'expériences sans code</h3>
              <p>Options faciles à utiliser et sans code pour la configuration, la personnalisation et l'affinement des expériences, permettant à un plus large éventail d'utilisateurs de travailler efficacement.</p>
            </div>
            <div class="highlight-item">
              <h3>Pipelines graphiques personnalisables</h3>
              <p>Options de personnalisation disponibles, permettant des pipelines sur mesure pour répondre aux exigences uniques du projet.</p>
            </div>
            <!-- Repeat for each feature -->
          </div>
          <!-- Center Image -->
          <div class="highlights-image">
            <img src="https://github.com/MahdiAll99/MEDomicsLab-website/blob/main/assets/media/ContributingTools.png?raw=true" alt="Tech Stack Icons">
          </div>
          <!-- Right Column -->
          <div class="highlights-column-left">
            <div class="highlight-item">
              <h3>Génération de code</h3>
              <p>Convertissez vos pipelines d'expérimentation en code modifiable pour une personnalisation plus poussée et une collaboration fluide avec les informaticiens. Améliorez le partage des connaissances en transformant les workflows visuels en framework de codage.</p>
            </div>
            <div class="highlight-item">
              <h3>Accès à la bibliothèque modulaire Python</h3>
              <p>Accès aux bibliothèques modulaires basées sur Python en back-end, pour ceux qui souhaitent approfondir le code personnalisé et les configurations expérimentales.</p>
            </div>
            <div class="highlight-item">
              <h3>Open source</h3>
              <p>Notre logiciel est facilement accessible et peut être modifié ou amélioré par n’importe qui.</p>
            </div>
          </div>
        </div>
        </section>
  

  - block: markdown
    id: download
    content:
      text: |
        <div style="text-align: center; margin: 1rem 0;">
          <h2 style="font-size: 2rem; font-weight: bold; margin-bottom: 0.5rem;">Disponible sur Windows, Linux et Mac</h2>
          <p style="font-size: 1.25rem; color: #555;">Téléchargez la plateforme MEDomics sur votre système d'exploitation préféré et commencez à explorer !</p>
        </div>
        <div class="download-section" style="display: flex; justify-content: space-between; gap: 2rem; margin: 0rem 0;">
          <!-- Windows Card -->
          <div style="flex: 1; text-align: center; border: 1px solid #e0e0e0; border-radius: 10px; padding: 1.5rem;">
            <img src="https://img.icons8.com/?size=512&id=TuXN3JNUBGOT&format=png" alt="Windows Logo" style="width: 200px; height:200px; margin-bottom: 1rem;">
            <h3>Windows</h3>
            <select id="windows-version" style="margin: 0.5rem 0; padding: 0.5rem; border: 1px solid #ccc; border-radius: 5px;">
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.4.0/MEDomicsLab-1.4.0-win.exe">Version 1.4.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.3.0/MEDomicsLab-1.3.0-win.exe">Version 1.3.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.2.0/MEDomicsLab-1.2.0-win.exe">Version 1.2.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.0.0/MEDomicsLab-1.0.0-win.exe">Version 1.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v0.0.5-prealpha/MEDomicsLab-0.0.5-prealpha-win.exe">Version 0.0.5-prealpha</option>
            </select>
            <a id="windows-download" href="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.0.0/MEDomicsLab-1.0.0-win.exe" 
              style="display: inline-block; margin-top: 1rem; padding: 0.75rem 1.5rem; background-color: #007bff; color: white; border-radius: 5px; text-decoration: none;">
              Télécharger
            </a>
          </div>

          <!-- Linux Card -->
          <div style="flex: 1; text-align: center; border: 1px solid #e0e0e0; border-radius: 10px; padding: 1.5rem;">
            <img src="https://cdn1.iconfinder.com/data/icons/operating-system-flat-1/30/linux-512.png" alt="Linux Logo" style="width: 200px; height:200px; margin-bottom: 1rem;">
            <h3>Linux</h3>
            <select id="linux-version" style="margin: 0.5rem 0; padding: 0.5rem; border: 1px solid #ccc; border-radius: 5px;">
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.4.0/MEDomicsLab-1.4.0-ubuntu.deb">Version 1.4.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.3.0/MEDomicsLab-1.3.0-ubuntu.deb">Version 1.3.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.2.0/MEDomicsLab-1.2.0-ubuntu.deb">Version 1.2.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.0.0/MEDomicsLab-1.0.0-ubuntu.deb">Version 1.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v0.0.5-prealpha/MEDomicsLab-0.0.5-prealpha-ubuntu.deb">Version 0.0.5-prealpha</option>
            </select>
            <a id="linux-download" href="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.0.0/MEDomicsLab-1.0.0-ubuntu.deb" 
              style="display: inline-block; margin-top: 1rem; padding: 0.75rem 1.5rem; background-color: #007bff; color: white; border-radius: 5px; text-decoration: none;">
              Télécharger
            </a>
          </div>

          <!-- Mac Card -->
          <div style="flex: 1; text-align: center; border: 1px solid #e0e0e0; border-radius: 10px; padding: 1.5rem;">
            <img src="https://img.icons8.com/?size=512&id=122959&format=png" alt="Mac Logo" style="width: 200px; height:200px; margin-bottom: 1rem;">
            <h3>Mac</h3>
            <select id="mac-version" style="margin: 0.5rem 0; padding: 0.5rem; border: 1px solid #ccc; border-radius: 5px;">
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.4.0/MEDomicsLab-1.4.0-mac.pkg">Version 1.4.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.3.0/MEDomicsLab-1.3.0-mac.pkg">Version 1.3.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.2.0/MEDomicsLab-1.2.0-mac.pkg">Version 1.2.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.0.0/MEDomicsLab-1.0.0-mac.pkg">Version 1.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v0.0.5-prealpha/MEDomicsLab-0.0.5-prealpha-mac.dmg">Version 0.0.5-prealpha</option>
            </select>
            <a id="mac-download" href="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.0.0/MEDomicsLab-1.0.0-mac.pkg" 
              style="display: inline-block; margin-top: 1rem; padding: 0.75rem 1.5rem; background-color: #007bff; color: white; border-radius: 5px; text-decoration: none;">
              Télécharger
            </a>
          </div>
        </div>

        <script>
          // Update download link when version changes
          document.getElementById("windows-version").addEventListener("change", function() {
            document.getElementById("windows-download").href = this.value;
          });
          document.getElementById("linux-version").addEventListener("change", function() {
            document.getElementById("linux-download").href = this.value;
          });
          document.getElementById("mac-version").addEventListener("change", function() {
            document.getElementById("mac-download").href = this.value;
          });
        </script>


  - block: cta-image-paragraph
    id: resources
    content:
      items:
        # Youtube
        - title: Contenu YouTube
          text: "Explorez notre chaîne YouTube pour :"
          feature_icon: check
          features:
            - "Tutoriels complets pour vous aider à démarrer"
            - "Tutoriels de modules individuels pour un apprentissage ciblé, étape par étape"
            - "Vidéos approfondies couvrant la phase de test complète de tous les modules"
            - "Conseils pour adapter l'application à vos besoins spécifiques"
          # Upload image to `assets/media/` and reference the filename here
          image: Youtube.png
          button:
            text: Commencer à regarder
            url: https://www.youtube.com/@MEDomicsLab
        
        # Documentation
        - title: Documentation
          text: "Consultez notre documentation pour :"
          # Upload image to `assets/media/` and reference the filename here
          feature_icon: check
          features:
            - "Guides d'installation pour toutes les plateformes"
            - "Explications détaillées des fonctionnalités de chaque module"
            - "Options avancées de personnalisation et d'expérimentation"
            - "Guides pour contribuer au projet"
          image: Documentation.png
          button:
            text: Commencer à lire
            url: https://medomics-udes.gitbook.io/medomicslab-docs/
          
        # Discord
        - title: GitHub
          text: "Consultez notre dépôt GitHub pour :"
          # Upload image to `assets/media/` and reference the filename here
          feature_icon: check
          features:
            - "Accès au code source complet de la plateforme MEDomics"
            - "Opportunités de contribuer au projet"
            - "Mises à jour régulières et nouvelles fonctionnalités"
            - "Soumission des problèmes et collaboration aux améliorations"
          image: GitHub.png
          button:
            text: Participez dans le développement
            url: https://github.com/MEDomicsLab/MEDomics

          # Discord
        - title: Discord
          text: Notre serveur Discord est un espace communautaire dynamique où les utilisateurs peuvent obtenir une assistance en temps réel, partager leurs idées et échanger avec d'autres utilisateurs et développeurs. Rejoignez-nous pour discuter des fonctionnalités, poser des questions et rester informé des dernières nouveautés.
          # Upload image to `assets/media/` and reference the filename here
          image: Discord.png
          button:
            text: Rejoignez notre Discord
            url: https://discord.com/invite/ZbaGj8E6mP
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
  
  - block: markdown
    id: supported-by
    content:
      title:  Soutenu par
      text: |
        <div style="text-align: center; width: 200px; ">
          <div style="display: flex; justify-content: center; gap: 250px; align-items: center;">
            <img src="https://resiproc.org/wp-content/uploads/2022/03/csm_udes_logo_rgb_c_1471ccc107.png" alt="Université de Sherbrooke" style="width: 500px;">
            <img src="https://repository-images.githubusercontent.com/257617359/0329b200-8555-11ea-9fe3-034058d6d354" alt="MEDomics" style="width: 300px;">
            <img src="https://ssaquebec.ca/wp-content/uploads/2022/04/Logo_Unite_SLOGAN_RGB_2021.png" alt="SSA Québec" style="width: 1300px;">
          </div>
        </div>

  - block: markdown
    id: acknowledgement
    content:
      title: Reconnaissance
      text: |
        <div style="text-align: center; ">
          <h6 style="font-size: 1.0em;">La plateforme MEDomics s'appuie sur ces outils essentiels</h6>
          <br><br>
          <img src="https://raw.githubusercontent.com/MahdiAll99/MEDomicsLab-website/refs/heads/main/assets/media/ToolsUsed.png"  alt="Outils essentiels pour la plateforme MEDomics" style="max-width: none; width: 1200px">
        </div>

---
