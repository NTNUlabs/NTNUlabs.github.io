---
# Leave the homepage title empty to use the site title
title:
date: 2025-05-01
type: landing

sections:
  - block: hero
    content:
      title: Welcome to the Intelligent Systems Lab!
      subtitle: Research in intelligent systems for maritime and robotics
      text: |
        Our research group is based under the MOVE research framework and belongs to <a href="https://www.ntnu.edu/ihb/department-of-ocean-operations-and-civil-engineering" target="_blank">the Department of Ocean Operations and Civil Engineering</a> under <a href="https://www.ntnu.edu/iv" target="_blank">the Faculty of Engineering</a>.
        The group consists of three full professors, one associate professor, three postdoctoral research fellows, and nine Ph.D. candidates.
      image:
        filename: togehter.jpg
        alt_text: Group photo
    design:
      alignment: right
      width: normal


  - block: markdown
    content:
      title: Research Focus
      text: |    
        The first research focus of the team is on digitalization of advanced marine systems, a field known for its multidisciplinary nature encompassing hydrodynamics, thermal analysis, control, etc. While conventional approaches typically involve the separate simulation of these subsystems, the team leading by Prof. Zhang pioneered the development of an integrated co-simulation framework for marine surface vessels, seamlessly incorporating over 10 multidisciplinary subsystems. The research works extended to the creation of a digital twin for marine vessels in real operation as the first, enabling remote monitoring and control of these complex systems. The second distinct research in the lab is in the area of physics-data cooperative hybrid modelling and control of marine vessels considering environmental and operational uncertainties. Unlike classic model-based or pure data-driven approaches, there have been few attempts to build predictive models by organically incorporating them together in a holistic manner. One of the primary reasons is that the model complexity due to frequent interaction with water results in an inaccurate description of marine vehicle dynamics. Furthermore, uncertainties and environmental disturbance including as operational conditional changing, wind and waves, add extra complexity and hinder obtaining ship dynamic model with high fidelity.
         {{% cta cta_link="./people/" cta_text="Meet the team" %}}
    design:
      columns: '1'
      
  # - block: collection
  #   content:
  #     title: Latest News
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: information.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  - block: markdown
    content:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team" %}}
    design:
      columns: '1'
---
