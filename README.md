name: "L6ECSIG Construction et utilisation des SIG"
navbar:
  left:
    - text: "Introduction"
      href: 01_intro.html
    - text: "Environnement"
      href: 02_environnement.html
    - text: "Bases R"
      href: 03_basesR.html 
    - text: "R spatial"
      href: 04_Rspatial.html
    - text: "Correction"
      href: 05_correction.html 
    - text: "Donnees"
      href: 06_Donnees.html 
    - text: "Traitement"
      href: 07_traitement.html   
    - text: "Resultat"
      href: 08_resultat.html   
  right:
    - icon: fa-github
      href: https://github.com/beababa/beababa.github.io
output: 
  html_document:
    toc_float: TRUE  
    theme: united
    highlight: tango
    include:
      after_body: footer.html
    number_sections: yes
    exclude: [data-raw, data]
    css: css/styles.css
