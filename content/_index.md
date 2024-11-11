---
title: 'Home'
date: 2024-11-11
type: landing

design:
  # Default section spacing
  spacing: "rem"

sections:
  - block: hero
    content:
      title: MEDomicsLab
      text:  Integrative Modeling of Heterogeneous Data in Medicine
      primary_action:
        text: Get Started
        url: https://medomics-udes.gitbook.io/MEDomicsLab-docs/quick-start
        icon: rocket-launch
      secondary_action:
        text: Explore tutorials
        url: https://youtube.com/@MEDomicsLab
      announcement:
        text: The first release is 
        link:
          text: here!
          url: https://github.com/MEDomics-UdeS/MEDomicsLab/releases
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
    id: overview
    
  - block: hero
    design:
      spacing:
        padding: [100, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        video:
          # Add your image background to `assets/media/`.
          filename: Promotional_Video.mp4

  - block: features
    id: dashboard
    content:
      title: All within a single dashboard
      text: One click away from your first predictive model
      items:
        - name: Easy management
          icon: sparkles
          description: MEDomicsLab simplifies the management of diverse datasets and assets, offering an organized, unified view of medical data. With its user-friendly interface, researchers can easily handle complex data without technical hurdles, making analysis more straightforward. 
        - name: Save your time
          icon: clock
          description: Equipped with all essential tools, MEDomicsLab saves users time by enabling experiment setup without any coding. Built-in pipelines and customizable workflows allow users to swiftly go from data to insights, boosting efficiency and focus on research.
        - name: Promote synergy
          icon: users
          description: Designed for collaboration, MEDomicsLab bridges the gap between clinicians and computer scientists. Clinicians can design experiments, while computer scientists can refine and adapt them, fostering teamwork for developing impactful predictive models.
  
  - block: markdown
    id: highlights
    content:
      title: Highlights
      text: |
        <style>
        .highlights {
          text-align: center;
          width: 2000px;
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
        <h1>The central features of MEDomicsLab</h1>
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
            <img src="https://static.wixstatic.com/media/f49584_f063e24bc948492ca83365132351ff66~mv2.png/v1/fill/w_366,h_627,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/ContributingToolsVerticalWShadow.png" alt="Tech Stack Icons">
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
            - "Guidance on tailoring the application to your specific needs"
            - "In-depth videos covering the full testing phase of all modules"
            - "Individual module tutorials for focused, step-by-step learning"
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
            - "Access to the full source code of MEDomicsLab"
            - "Opportunities to contribute to the project"
            - "Regular updates and new feature releases"
            - "Issues submission and collaboration on improvements"
          image: GitHub.png
          button:
            text: Join our Development
            url: https://github.com/MEDomics-UdeS/MEDomicsLab

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
          <div style="display: flex; justify-content: center; gap: 50px; align-items: center;">
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
          <h6 style="font-size: 1.0em;">MEDomicsLab relies on these essential tools</h6>
          <img src="https://static.wixstatic.com/media/f49584_6afd83e505e649b188ea0aea7bdc1d90~mv2.png/v1/fill/w_904,h_277,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/PackagesUsed.png"  alt="MEDomicsLab essential packages">
        </div>

---
