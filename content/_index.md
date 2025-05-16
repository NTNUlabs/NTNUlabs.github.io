---
title: ""
date: 2025-04-30
type: landing

sections:
- block: markdown
  content:
    text: |
      <div class="custom-homepage">
        <div class="home-left">
          <img src="/media/logo.jpg" alt="Lab Logo" />
          <h2>Intelligent Systems Lab</h2>
          <p>Norges teknisk-naturvitenskapelige universitet</p>
          <a href="https://www.ntnu.edu/ihb/intelligent-systems-lab">
            <i class="fas fa-house fa-lg"></i>
          </a>
          <a href="https://twitter.com/NTNU_ISL">
            <i class="fab fa-twitter fa-lg"></i>
          </a>
          <a href="https://www.youtube.com/channel/UC4zkSMXSMHyTlepIwaylY_A">
            <i class="fab fa-youtube fa-lg"></i>
          </a>
          <a href="https://github.com/NTNUlabs/NTNUlabs.github.io">
            <i class="fab fa-github fa-lg"></i>
          </a>
        </div>

        <div class="home-right">
          <h1>Welcome to the Intelligent Systems Lab!</h1>
          <p>
            The Intelligent Systems Lab is run by
            <a href="http://127.0.0.1:1313/authors/houxiang%20zhang/">Houxiang Zhang</a>.
            Our research group is based under the MOVE research framework and belongs to
            <a href="https://www.ntnu.edu/ihb/department-of-ocean-operations-and-civil-engineering" target="_blank">
              the Department of Ocean Operations and Civil Engineering</a> under
            <a href="https://www.ntnu.edu/iv" target="_blank">the Faculty of Engineering</a>.
            The group consists of three full professors, one associate professor, three postdoctoral research fellows, and nine Ph.D. candidates.
          </p>
          <img src="media/together.jpg" alt="Group Photo" />

         
        </div>
      </div>
- block: markdown
  content:
    text: |
      <section style="padding: 0rem 1rem 0 4rem; max-width: 1400px; width: 90%; margin: auto;">
        <h2 style="font-size: 2rem; margin-bottom: 1rem; text-align: center;">Our Research Focus</h2>
        <p style="font-size: 1.05rem; line-height: 1.75; margin-bottom: 1rem;">
          The first research focus of the team is on digitalization of advanced marine systems, a field known for its multidisciplinary nature encompassing hydrodynamics, 
          thermal analysis, control, etc. While conventional approaches typically involve the separate simulation of these subsystems, the team led by Prof. Zhang pioneered 
          the development of an integrated co-simulation framework for marine surface vessels, incorporating over 10 multidisciplinary subsystems.
        </p>
        <p style="font-size: 1.05rem; line-height: 1.75;">
          The second research focus is in the area of physics-data cooperative hybrid modeling and control of marine vessels, considering environmental and operational uncertainties.
          This combines physics-based models with data-driven techniques to achieve more robust, adaptive, and interpretable system behaviors.
        </p>
      </section>

- block: team
  content: {}

- block: collection
  content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
  design:
      view: citation
      columns: '1'

- block: markdown
  content:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  design:
      columns: '1'


---