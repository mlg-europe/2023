---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: 20th MLG workshop 
      #image:
      #  filename: Turin_monte_cappuccini.jpg
      cta:
        label: '**Call for Papers**'
        url: https://wowchemy.com/templates/
      #cta_alt:
      #  label: Ask a question
      #  url: https://discord.gg/z8wNYzb
      text: |-
        **20th International Workshop on
        <br />
        Mining and Learning with Graphs**

        22nd of September 2023

        Torino, Italy

        In conjunction with ECMLPKDD 2023
    design:
      background:
        #gradient_end: '#1976d2'
        #gradient_start: '#004ba0'
        text_color_light: true
        image:
          # Name of image in `assets/media/`.
          filename:  Turin_monte_cappuccini.jpg
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0.6
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
          

  - block: people
    content:
      title: Tutorial
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - tutorial-speaker
    design:
      # Show user's social networking links? (true/false)
      show_social: false
      # Show user's interests? (true/false)
      show_interests: false
      # Show user's role?
      show_role: false
      # Show user's organizations/affiliations?
      show_organizations: true

  - block: people
    content:
      title: Keynotes
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - keynote-speaker
    design:
      # Show user's social networking links? (true/false)
      show_social: false
      # Show user's interests? (true/false)
      show_interests: false
      # Show user's role?
      show_role: false
      # Show user's organizations/affiliations?
      show_organizations: true

  - block: markdown
    content:
      id: CFP
      title: Call for Papers
      text:
        This workshop is a forum for exchanging ideas and methods for mining and learning with graphs, developing new common understandings of the problems at hand, sharing of data sets where applicable, and leveraging existing knowledge from different disciplines. The goal is to bring together researchers from academia and industry, to create a forum for discussing recent advances in graph analysis. 
        In doing so, we aim to better understand the overarching principles and the limitations of current methods and to inspire research on new algorithms and techniques for mining and learning with graphs.

        To reflect the broad scope of work on mining and learning with graphs, we encourage submissions that span the spectrum from theoretical analysis to algorithms and implementation, to applications and empirical studies. 
        We are interested in the full spectrum of graph data, including but not limited to attributed graphs, labeled graphs, knowledge graphs, evolving graphs, transactional graph databases, etc.

        We therefore invite submissions on \emph{theoretical aspects, algorithms and methods,} and \emph{applications} of the following (non-exhaustive) list of areas:}

        - Computational or statistical learning theory related to graphs
        - Theoretical analysis of graph algorithms or models
        - Semi-supervised learning, online learning, active learning, transductive inference, and transfer learning in the context of graphs
        - Unsupervised learning and graph clustering
        - Interesting pattern mining on graphs and community detection
        - Graph kernels and metric learning on graphs
        - Graph and vertex embeddings and representation learning on graphs
        - Solving combinatorial problems on graphs with ML / data driven combinatorial optimization
        - Explainable, fair, robust, and/or privacy preserving ML on graphs
        - Statistical models of graphs and graph sampling
        - Analysis of social media, chemical or biological networks, infrastructure networks, knowledge graphs
        - Benchmarking aspects of graph based learning
        - Libraries and tools for all of the above areas
        
        We welcome many kinds of papers, such as, but not limited to:

        - Novel research papers
        - Demo papers
        - Dataset papers
        - Work-in-progress papers
        - Visionary papers (white papers)
        - Appraisal papers of existing methods and tools (e.g., lessons learned)
        - Relevant work that has been previously published
        - Work that will be presented at the main conference (can be submitted with the regular 16 page limit of ECMLPKDD)
        
        Authors should clearly indicate in their abstracts the kinds of submissions that the papers belong to, to help reviewers better understand their contributions.
        All papers will be (single blind) peer reviewed. 
        Submissions must be in PDF, long papers no more than 12 pages long, short papers  no more than 8 pages long, formatted according to the standard Springer LNCS style required for ECMLPKDD submissions.
        The accepted papers will be published on the workshop’s website and will not be considered archival for resubmission purposes.
        Authors whose papers are accepted to the workshop will have the opportunity to participate in a pitch and poster session, and the best two will also be chosen for oral presentation.

        Dual Submission Policy
        We accept submissions that are currently under review at other venues. 
        However, in this case our page limits apply.
        Please also check the dual submission policy of the other venue.
            

  - block: people
    content:
      title: Organizers
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - PC
    design:
      # Show user's social networking links? (true/false)
      show_social: false
      # Show user's interests? (true/false)
      show_interests: false
      # Show user's role?
      show_role: false
      # Show user's organizations/affiliations?
      show_organizations: true
---
