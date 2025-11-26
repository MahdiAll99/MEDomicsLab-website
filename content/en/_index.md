---
title: 'Home'
date: 2024-11-11
type: landing

design:
  # Default section spacing
  spacing: "rem"

sections:
  - block: announcement
    design:
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: [0, 0, 0, 0]
      
  - block: hero
    content:
      title: MEDomics platform
      text:  Integrative Modeling of Heterogeneous Data in Medicine
      primary_action:
        text: Get Started
        url: https://medomics-udes.gitbook.io/medomicslab-docs/
        icon: rocket-launch
      secondary_action:
        text: Explore tutorials
        url: https://youtube.com/@MEDomicsLab
      announcement:
        text: The first release is 
        link:
          text: here!
          url: /#download
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
      title: Discover the MEDomics platform
      text: |
        <div style="text-align: center;">
          <iframe width="1280" height="720" src="https://www.youtube.com/embed/JUTxSSsKlEc?si=SnqmwxbV5wj6sdyT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>

  - block: features
    id: dashboard
    content:
      title: All within a single dashboard
      text: One click away from your first predictive model
      items:
        - name: Easy management
          icon: sparkles
          description: MEDomics platform simplifies the management of diverse datasets and assets, offering an organized, unified view of medical data. With its user-friendly interface, researchers can easily handle complex data without technical hurdles, making analysis more straightforward. 
        - name: Save your time
          icon: clock
          description: Equipped with all essential tools, MEDomics platform saves users time by enabling experiment setup without any coding. Built-in pipelines and customizable workflows allow users to swiftly go from data to insights, boosting efficiency and focus on research.
        - name: Promote synergy
          icon: users
          description: Designed for collaboration, MEDomics platform bridges the gap between clinicians and computer scientists. Clinicians can design experiments, while computer scientists can refine and adapt them, fostering teamwork for developing impactful predictive models.

  - block: markdown
    id: highlights
    content:
      title: Highlights
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
        <h1>The central features of the MEDomics platform</h1>
         <div class="highlights-content">
          <!-- Left Column -->
          <div class="highlights-column-right">
            <div class="highlight-item">
              <h3>Unified Dashboard</h3>
              <p>A central hub where users can manage datasets, train predictive models, and run various experiments without switching between tools.</p>
            </div>
            <div class="highlight-item">
              <h3>No-Code Experiment Design</h3>
              <p>Easy-to-use, no-code options for setting up, customizing, and refining experiments, enabling a wider range of users to work effectively.</p>
            </div>
            <div class="highlight-item">
              <h3>Customizable Graphical Pipelines</h3>
              <p>Available customization options, allowing tailored pipelines to fit unique project requirements.</p>
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
              <h3>Code Generation</h3>
              <p>Convert your experiment pipelines into editable code for deeper customization, and seamless collaboration with computer scientists. A better knowledge-sharing by transforming visual workflows into a coding framework</p>
            </div>
            <div class="highlight-item">
              <h3>Python Modular Library Access</h3>
              <p>Access to Python-based modular libraries on the back-end, for those who wish to dive deeper into custom code and experimental setups.</p>
            </div>
            <div class="highlight-item">
              <h3>Open source</h3>
              <p>Our software program is readily accessible and can be modified or enhanced by anyone.</p>
            </div>
          </div>
        </div>
        </section>
  

  - block: markdown
    id: download
    content:
      text: |
        <div style="text-align: center; margin: 1rem 0;">
          <h2 style="font-size: 2rem; font-weight: bold; margin-bottom: 0.5rem;">Available on Windows, Linux, and Mac</h2>
          <p style="font-size: 1.25rem; color: #555;">Download the MEDomics platform on your favorite operating system and start exploring!</p>
        </div>
        <div class="download-section" style="display: flex; justify-content: space-between; gap: 2rem; margin: 0rem 0;">
          <!-- Windows Card -->
          <div style="flex: 1; text-align: center; border: 1px solid #e0e0e0; border-radius: 10px; padding: 1.5rem;">
            <img src="https://img.icons8.com/?size=512&id=TuXN3JNUBGOT&format=png" alt="Windows Logo" style="width: 200px; height:200px; margin-bottom: 1rem;">
            <h3>Windows</h3>
            <select id="windows-version" style="margin: 0.5rem 0; padding: 0.5rem; border: 1px solid #ccc; border-radius: 5px;">
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.6.0/MEDomics-1.6.0-win.exe">Version 1.6.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.5.0/MEDomicsLab-1.5.0-win.exe">Version 1.5.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.4.0/MEDomicsLab-1.4.0-win.exe">Version 1.4.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.3.0/MEDomicsLab-1.3.0-win.exe">Version 1.3.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.2.0/MEDomicsLab-1.2.0-win.exe">Version 1.2.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.0.0/MEDomicsLab-1.0.0-win.exe">Version 1.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v0.0.5-prealpha/MEDomicsLab-0.0.5-prealpha-win.exe">Version 0.0.5-prealpha</option>
            </select>
            <a id="windows-download" href="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.6.0/MEDomics-1.6.0-win.exe" 
              style="display: inline-block; margin-top: 1rem; padding: 0.75rem 1.5rem; background-color: #007bff; color: white; border-radius: 5px; text-decoration: none;">
              Download
            </a>
          </div>

          <!-- Linux Card -->
          <div style="flex: 1; text-align: center; border: 1px solid #e0e0e0; border-radius: 10px; padding: 1.5rem;">
            <img src="https://cdn1.iconfinder.com/data/icons/operating-system-flat-1/30/linux-512.png" alt="Linux Logo" style="width: 200px; height:200px; margin-bottom: 1rem;">
            <h3>Linux</h3>
            <select id="linux-version" style="margin: 0.5rem 0; padding: 0.5rem; border: 1px solid #ccc; border-radius: 5px;">
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.6.0/MEDomics-1.6.0-ubuntu.deb">Version 1.6.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.5.0/MEDomicsLab-1.5.0-linux.deb">Version 1.5.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.4.0/MEDomicsLab-1.4.0-ubuntu.deb">Version 1.4.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.3.0/MEDomicsLab-1.3.0-ubuntu.deb">Version 1.3.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.2.0/MEDomicsLab-1.2.0-ubuntu.deb">Version 1.2.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.0.0/MEDomicsLab-1.0.0-ubuntu.deb">Version 1.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v0.0.5-prealpha/MEDomicsLab-0.0.5-prealpha-ubuntu.deb">Version 0.0.5-prealpha</option>
            </select>
            <a id="linux-download" href="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.6.0/MEDomics-1.6.0-ubuntu.deb" 
              style="display: inline-block; margin-top: 1rem; padding: 0.75rem 1.5rem; background-color: #007bff; color: white; border-radius: 5px; text-decoration: none;">
              Download
            </a>
          </div>

          <!-- Mac Card -->
          <div style="flex: 1; text-align: center; border: 1px solid #e0e0e0; border-radius: 10px; padding: 1.5rem;">
            <img src="https://img.icons8.com/?size=512&id=122959&format=png" alt="Mac Logo" style="width: 200px; height:200px; margin-bottom: 1rem;">
            <h3>Mac</h3>
            <select id="mac-version" style="margin: 0.5rem 0; padding: 0.5rem; border: 1px solid #ccc; border-radius: 5px;">
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.6.0/MEDomics-1.6.0-mac.pkg">Version 1.6.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.5.0/MEDomicsLab-1.5.0-mac.pkg">Version 1.5.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.4.0/MEDomicsLab-1.4.0-mac.pkg">Version 1.4.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.3.0/MEDomicsLab-1.3.0-mac.pkg">Version 1.3.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.2.0/MEDomicsLab-1.2.0-mac.pkg">Version 1.2.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.0.0/MEDomicsLab-1.0.0-mac.pkg">Version 1.0</option>
              <option value="https://github.com/MEDomicsLab/MEDomics/releases/download/v0.0.5-prealpha/MEDomicsLab-0.0.5-prealpha-mac.dmg">Version 0.0.5-prealpha</option>
            </select>
            <a id="mac-download" href="https://github.com/MEDomicsLab/MEDomics/releases/download/v1.6.0/MEDomics-1.6.0-mac.pkg" 
              style="display: inline-block; margin-top: 1rem; padding: 0.75rem 1.5rem; background-color: #007bff; color: white; border-radius: 5px; text-decoration: none;">
              Download
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
        - title: Youtube content
          text: "Explore our YouTube channel for:"
          feature_icon: check
          features:
            - "Comprehensive tutorials to help you get started"
            - "Individual module tutorials for focused, step-by-step learning"
            - "In-depth videos covering the full [**testing phase**](https://medomics-udes.gitbook.io/medomicslab-docs/medomicslab-docs-v0/test-with-mimic) of all modules"
            - "Guidance on tailoring the application to your specific needs"
          # Upload image to `assets/media/` and reference the filename here
          image: Youtube.png
          button:
            text: Start watching
            url: https://www.youtube.com/@MEDomicsLab
        
        # Documentation
        - title: Documentation
          text: "Check out our documentation for:"
          # Upload image to `assets/media/` and reference the filename here
          feature_icon: check
          features:
            - "Installation guides for all platforms"
            - "In-depth explanations of each module's features"
            - "Advanced options for customization and experimentation"
            - "Guides for contributing to the project"
          image: Documentation.png
          button:
            text: Start reading
            url: https://medomics-udes.gitbook.io/medomicslab-docs/
          
        # Discord
        - title: GitHub
          text: "Check out our GitHub repository for:"
          # Upload image to `assets/media/` and reference the filename here
          feature_icon: check
          features:
            - "Access to the full source code of the MEDomics platform"
            - "Opportunities to contribute to the project"
            - "Regular updates and new feature releases"
            - "Issues submission and collaboration on improvements"
          image: GitHub.png
          button:
            text: Join our Development
            url: https://github.com/MEDomicsLab/MEDomics

          # Discord
        - title: Discord
          text: Our Discord server is a vibrant community hub where users can get real-time support, share insights, and connect with fellow users and developers. Join us to discuss features, ask questions, and stay updated on the latest releases.
          # Upload image to `assets/media/` and reference the filename here
          image: Discord.png
          button:
            text: Join our Discord
            url: https://discord.com/invite/ZbaGj8E6mP
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
  
  - block: markdown
    id: supported-by
    content:
      title: Supported by
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
      title: Acknowledgement
      text: |
        <div style="text-align: center; ">
          <h6 style="font-size: 1.0em;">MEDomics platform relies on these essential tools</h6>
          <br><br>
          <img src="https://raw.githubusercontent.com/MahdiAll99/MEDomicsLab-website/refs/heads/main/assets/media/ToolsUsed.png"  alt="MEDomics platform essential packages" style="max-width: none; width: 1200px">
        </div>

---
