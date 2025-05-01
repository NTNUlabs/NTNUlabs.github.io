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
        filename: toghter.jpg
        alt_text: Group photo
    design:
      alignment: right
      width: normal

  - block: markdown
    content:
      title: Our Projects
      text: |
        ### Overview

        Demanding Marine Operations is a core of the maritime industry...

        ### List {align=right}

        - [SFI MOVE (2015–2023)](/project/#sfi-move)
        - [Arrowhead Tools (2019–2022)](/project/#arrowhead)
    design:
      columns: '2'
      gap: 64


  - block: markdown
    content:
      title: Research Focus
      text: |    
        The first research focus of the team is on digitalization of advanced marine systems, a field known for its multidisciplinary nature encompassing hydrodynamics, thermal analysis, control, etc...

        The second distinct research in the lab is in the area of physics-data cooperative hybrid modelling and control of marine vessels...

  - block: collection
    content:
      title: Latest News
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team" %}}
    design:
      columns: '1'
---
