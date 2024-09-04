---
# Leave the homepage title empty to use the site title
title: ""
#date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: research
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
              I am mostly interested in the study of singular SPDEs using the tools from paracontrolled calculus. I defended my PhD thesis "Anderson stochastic quantization and paracontrolled calculus : stochastic PDEs in a singular environment." in June 2024 and am currently working  on related topics at UMPA, ENS Lyon, under the supervision of Nikolay Tzvetkov.
    design:
       columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured papers
      text: ''
      filters:
        folders:
          - post
    design:
      columns: '1'
      view: cardview-for-publications
  - block: markdown
    id: talks
    content: 
      title: Past and upcoming talks
      text: |- 
            - January 2024, Nicolas Perkowski’s team seminar, Freie Universität, Berlin.
            - October 2023, Landau seminar, IRMAR, Rennes.
            - June 2023, ANR Smooth Workshop, Institut Elie Cartan de Lorraine, Nancy.
            - October 2022, Nicolas Perkowski’s team seminar, Freie Universität, Berlin.
            - May 2022, ”Rough paths, stochastic partial differential equations and related topics” seminar, Technische Universität, Berlin.
    design:
      columns: '1'
  # - block: markdown
  #   id: conf
  #   content: 
  #     title: Conferences and workshops
  #     text: |- 
  #           - May 2024, Turbulent.e.s workshop, Ecole Polytechnique
  #           - October 2023, ANR Smooth Workshop, Institut Elie Cartan de Lorraine, Nancy.
  #           - September 2023, CIME summer school Statistical Mechanics and Stochastic PDEs, Cetraro.
  #           - July 2023, SPDEvent II, Universität Bielefeld.
  #           - June 2023, GDR TRAG workshop, Paris-Dauphine University.
  #           - June 2022, GDR TRAG workshop, Paris-Nanterre University.
  #           - December 2021, Young TRAG workshop, IHP, Paris.
  #           - November 2021, Higher Structures Emerging from Renormalisation, Erwin Schrödinger Institüt, Vienna.
  #   design:
  #     columns: '1'    
  - block: collection
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - teaching
    design:
      view: card
      columns: '1'
  
---
