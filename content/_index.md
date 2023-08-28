---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    id: home
    content:
      title: 20th MLG workshop 
      #image:
      #  filename: Turin_monte_cappuccini.jpg
      cta:
        label: '**Call for Papers**'
        url: '#cfp'
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

  - block: markdown
    content:
        title: 

  - block: markdown
    id: intro
    content:
       title: Introduction
       name: intro
       text: |-
         There is a great deal of interest in analyzing data that is best represented as a graph. 
         Examples include the WWW, social networks, biological networks, communication networks, transportation networks, energy grids, and many others. 
         These graphs are typically multi-modal, multi-relational, and dynamic. 
         The importance of being able to effectively mine and learn from such data is growing, as more and more structured and semi-structured data is 
         becoming available. Effectively learning from this kind of data poses several challenging problems, including:
        
         * The necessity of a plethora of different techniques, including graph mining algorithms, graph embedding techniques, and other learning algorithms on graphs.
         * Dealing with the heterogeneity of the data as well as information integration and alignment.
         * Handling dynamic and changing data.
         * Addressing each of these issues at scale.
        
         Traditionally, a number of subareas have contributed to this space: 
         communities in graph mining, learning from structured data, statistical relational learning, inductive logic programming, 
         social network analysis, and network science. Our workshop will serve as a forum for researchers from this variety of fields working on mining 
         and learning with graphs to share and discuss their latest findings.

  - block: markdown
    id: importantdates
    content:
      title: Important Dates
      text: |-
        <div style="margin-left: auto;
            margin-right: auto;
            width: 45%">

        **Paper Submission Deadline:** ~~June 12th~~ June 18th (11:59pm, [AoE](https://time.is/Anywhere_on_Earth)) 2023

        **Author Notification:** July 12th 2023

        **Camera Ready:** September 4th  2023

        **Workshop:** September 22rd 2023

        </div>

  - block: people
    id: tutorial
    content:
      title: Tutorial
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - tutorial-speaker
      text: |-
        **Deep learning on graphs tutorial**

        The tutorial will introduce the audience to the area of deep learning for graphs and its applications. Dealing with graph data requires learning models capable of adapting to structured samples of varying size and topology, capturing the relevant structural patterns to perform predictive and explorative tasks while maintaining the efficiency and scalability necessary to process large scale networks. The tutorial will first introduce foundational aspects and seminal models for learning with graph structured data. Then it will delve into the details of the predominant paradigm in deep learning for graphs, that is neural message-passing, and discuss its reference literature models. It will conclude with a brief discussion on the limitations of these approaches and the research opportunities that are stemming from this.

          <div style="margin-left: auto;
            margin-right: auto;
            width: 35%"></div>
    design:
      # Show user's social networking links? (true/false)
      show_social: true
      # Show user's interests? (true/false)
      show_interests: false
      # Show user's role?
      show_role: false
      # Show user's organizations/affiliations?
      show_organizations: true

  - block: people
    id: keynotes
    content:
      title: Keynotes
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - keynote-speaker
    design:
      # Show user's social networking links? (true/false)
      show_social: true
      # Show user's interests? (true/false)
      show_interests: false
      # Show user's role?
      show_role: false
      # Show user's organizations/affiliations?
      show_organizations: true


  - block: markdown
    id: schedule
    content:
        title: Schedule
        text: |-
          
          <div align="center" style="margin-left: auto;
            margin-right: auto;
            width: 100%">

          Torino, Italy (all times are [CEST](https://time.is/CEST))
          </div>

          <div align="center" style="margin-left: auto;
            margin-right: auto;
            width: 100%">

          All accepted papers will be presented in the poster session.
          
          <br />
          </div>

          <div style="margin-left: auto;
            margin-right: auto;
            width: 60%">
          <style>
          tr:nth-child(even) {
            background-color: #DDDDDD!important;
          }
          </style>


          |       | Schedule                              |
          |-------|---------------------------------------|
          | 08:55 | Opening                               |
          | 09:00 | <b>Tutorial</b> by Davide Bacciu             |
          | 10:45 | Coffee break                          |
          | 11:00 | <b>The expressive power of pooling in Graph Neural Networks</b><br /> by Filippo Maria Bianchi and Veronica Lachi                   |
          | 11:15 | <b>Decoding Over-Smoothing and Over-Correlation: Towards Powerful Graph Neural Networks</b><br /> by Andreas Roth and Thomas Liebig                   |
          | 11:30 | <b>Pitch talks</b> (group A)                           |
          | 12:00 | <b>Poster session</b> (group A)              |
          | 13:00 | Lunch break                           |
          | 14:00 | <b>Keynote</b> by Giannis Nikolentzos        |
          | 14:45 | <b>Removing Redundancy in Graph Neural Networks</b><br /> by Franka Bause et al.                   |
          | 15:00 | <b>A Fractional Graph Laplacian Approach to Oversmoothing</b><br /> by Sohir Maskey et al.               |
          | 15:15 | Coffee break with topical discussions |
          | 15:45 | <b>Keynote</b> by Bastian Rieck              |
          | 16:30 | <b>Pitch talks</b> (group B)                           |
          | 17:00 | <b>Poster session</b> (group B)              |
          | 18:00 | Conclusion & awards                   |
          </div>

  - block: markdown 
    id: awards
    content:
        title: Awards
        text: |-
          <div style="margin-left: auto;
            margin-right: auto;
            width: 5%">
            TBC
          </div>

  - block: markdown
    id: accepted
    content:
        title: Accepted Papers
        text: |-
          <div style="margin-left: auto;
            margin-right: auto;
            width: 75%">

            <table>
            <tr><td>
            <b>Edge Directionality Improves Learning on Heterophilic Graphs</b><br />
            Emanuele Rossi*, Bertrand Charpentier, Francesco Di Giovanni, Fabrizio Frasca, Stephan Günnemann, Michael Bronstein
            </td></tr>

            <tr><td>
            <b>On a linear fused Gromov-Wasserstein distance for graph structured data</b><br />
            Dai Hai Nguyen*
            </td></tr>

            <tr><td>
            <b>TAMARA: a task-aware multilayer graph simplification framework</b><br />
            Cheick Tidiane Ba*, Roberto Interdonato, Dino Ienco, sabrina gaito
            </td></tr>

            <tr><td>
            <b>Curvature-based Pooling within Graph Neural Networks</b><br />
            Cedric Sanders, Andreas Roth*, Thomas Liebig
            </td></tr>

            <tr><td>
            <b>Decoding Over-Smoothing and Over-Correlation: Towards Powerful Graph Neural Networks</b><br />
            Andreas Roth*, Thomas Liebig
            </td></tr>

            <tr><td>
            <b>GeNNius: An ultrafast drug-target interaction inference method based on graph neural networks </b><br />
            Uxía Veleiro*, Jesús de la Fuente, Guillermo Serrano, Marija Pizurica, Mikel Casals, Antonio Pineda-Lucena, Silve Vicent, Idoia Ochoa, Olivier Gevaert, Mikel Hernaez
            </td></tr>

            <tr><td>
            <b>The expressive power of pooling in Graph Neural Networks</b><br />
            Filippo Maria Bianchi, Veronica Lachi*
            </td></tr>

            <tr><td>
            <b>Graph Neural Networks for Graph Drawing</b><br />
            Matteo Tiezzi*, Gabriele Ciravegna, Marco Gori
            </td></tr>

            <tr><td>
            <b>Graph Neural Networks for temporal graphs: State of the art, open challenges, and opportunities</b><br />
            Antonio Longa, Veronica Lachi*, Gabriele Santin, Monica Bianchini, Bruno Lepri, Pietro Lió, Franco Scarselli, Andrea Passerini
            </td></tr>

            <tr><td>
            <b>Investigating the Interplay between Features and Structures in Graph Learning</b><br />
            Daniele Castellana*, Federico Errica
            </td></tr>

            <tr><td>
            <b>Finding coherent node groups in directed graphs</b><br />
            Iiro Kumpulainen*, Nikolaj Tatti
            </td></tr>

            <tr><td>
            <b>Hypergraphx: a library for higher-order network analysis</b><br />
            Quintino Francesco Lotito*, Martina Contisciani, Caterina De Bacco, Leonardo Di Gaetano, Luca Gallo, Alberto Montresor, Federico Musciotto, Nicolò Ruggeri, Federico Battiston
            </td></tr>

            <tr><td>
            <b>Balancing performance and complexity with adaptive graph coarsening</b><br />
            Marek Dědič*, Lukáš Bajer, Pavel Procházka, Martin Holena
            </td></tr>

            <tr><td>
            <b>Global Explainability of GNNs via Logic Combination of Learned Concepts</b><br />
            Steve Azzolin, Antonio Longa*, Pietro Barbiero, Pietro Lió, Andrea Passerini
            </td></tr>

            <tr><td>
            <b>Understanding how explainers work in graph neural networks</b><br />
            Antonio Longa*, Steve Azzolin, Gabriele Santin, Giulia Cencetti, Pietro Lió, Bruno Lepri, Andrea Passerini
            </td></tr>

            <tr><td>
            <b>Over-Parameterized Neural Models based on Graph Random Features for fast and accurate graph classification</b><br />
            Nicolò Navarin*, Luca Pasa, Claudio Gallicchio, Luca Oneto, Alessandro Sperduti)
            </td></tr>

            <tr><td>
            <b>Compositional Visual Causal Reasoning with Language Prompts</b><br />
            Krishna Sri Ipsit Mantri*, Nevasini NA Sasikumar
            </td></tr>

            <tr><td>
            <b>Removing Redundancy in Graph Neural Networks</b><br />
            Franka Bause*, Samir Moustafa, Wilfried Gansterer, Nils M Kriege
            </td></tr>

            <tr><td>
            <b>SILVAN: Estimating Betweenness Centralities with Progressive Sampling and Non-uniform Rademacher Bounds</b><br />
            Leonardo Pellegrina*, Fabio Vandin
            </td></tr>

            <tr><td>
            <b>Exploring the Poincaré Ellipsis</b><br />
            Samuel G. Fadel*, Tino Paulsen, Ulf Brefeld
            </td></tr>

            <tr><td>
            <b>A Fractional Graph Laplacian Approach to Oversmoothing</b><br />
            Sohir Maskey*, Raffaele Paolino, Aras Bacho, Gitta Kutyniok
            </td></tr>
            </table>


          </div>

  - block: markdown
    id: cfp
    content:
        title: Call for papers
        text: |-
          This workshop is a forum for exchanging ideas and methods for mining and learning with graphs, developing new common understandings of the problems at hand, sharing of data sets where applicable, and leveraging existing knowledge from different disciplines. The goal is to bring together researchers from academia and industry, to create a forum for discussing recent advances in graph analysis. In doing so, we aim to better understand the overarching principles and the limitations of current methods and to inspire research on new algorithms and techniques for mining and learning with graphs.

          To reflect the broad scope of work on mining and learning with graphs, we encourage submissions that span the spectrum from theoretical analysis to algorithms and implementation, to applications and empirical studies. We are interested in the full spectrum of graph data, including but not limited to attributed graphs, labeled graphs, knowledge graphs, evolving graphs, transactional graph databases, etc.

          We therefore invite submissions on theoretical aspects, algorithms and methods, and applications of the following (non-exhaustive) list of areas:

          * Computational or statistical learning theory related to graphs
          * Theoretical analysis of graph algorithms or models
          * Semi-supervised learning, online learning, active learning, transductive inference, and transfer learning in the context of graphs
          * Unsupervised learning and graph clustering
          * Interesting pattern mining on graphs and community detection
          * Graph kernels and metric learning on graphs
          * Graph and vertex embeddings and representation learning on graphs
          * Solving combinatorial problems on graphs with ML / data driven combinatorial optimization
          * Explainable, fair, robust, and/or privacy preserving ML on graphs
          * Statistical models of graphs and graph sampling
          * Analysis of social media, chemical or biological networks, infrastructure networks, knowledge graphs
          * Benchmarking aspects of graph based learning
          * Libraries and tools for all of the above areas

          **We welcome many kinds of papers**, such as, but not limited to:

          * Novel research papers
          * Demo papers
          * Visionary papers (white papers)
          * Appraisal papers of existing methods and tools (e.g., lessons learned)
          * Relevant work that has been previously published
          * Work that will be presented at the main conference (incl. research, ADS, or journal track; can be submitted in full length ignoring our page limit)

          Authors must clearly indicate in their abstracts the kinds of submissions that the papers belong to, to help reviewers better understand their contributions. All papers will be (single blind) peer reviewed. 

          **Submissions** must be in PDF, long papers no more than 12 pages long, short papers no more than 8 pages long, formatted according to the standard [Springer LNCS style](https://resource-cms.springernature.com/springer-cms/rest/v1/content/19238648/data/v6) required for ECMLPKDD submissions. Authors can use unlimited additional pages for references and appendices. 

          All accepted papers will be published on the workshop’s website. Unpublished submissions (e.g., novel research papers, novel demo papers, novel visionary papers, and novel appraisal papers) will additionally be considered for inclusion in the ECMLPKDD workshop proceedings in the Springer CCIS series. This is an opt-in process.
          Website publication will not be considered archival for resubmission purposes. Authors whose papers are accepted to the workshop will pitch their work to the full audience and will participate in a poster session. The best two submissions will also be chosen for a long oral presentation.


          Please note that at least one author of each accepted paper has to register for the conference.

          **Dual Submission Policy**: We accept submissions that are currently under review at other venues. However, in this case our page limits apply. Please also check the dual submission policy of the other venue.

          For paper submission, please proceed to our [submission page](https://cmt3.research.microsoft.com/ECMLPKDDworkshop2023). When submitting a paper make sure to select the correct track "MLG: Mining and Learning with Graphs" from the list of workshops.

          Please send enquiries to pascal.welke@tuwien.ac.at.
  
  - block: people
    id: organizers
    content:
      title: Organizers
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - PC

      sort_by: Params.first_name
      sort_ascending: true
    design: 
      # Show user's social networking links? (true/false)
      show_social: true
      # Show user's interests? (true/false)
      show_interests: false
      # Show user's role?
      show_role: false
      # Show user's organizations/affiliations?
      show_organizations: true

      
  - block: markdown
    id: pc
    content:
        title:  Program Committee
        text: |-
          
          <div style="
              display: flex;
              justify-content: center;"
            > 

            <style>
            ol {
              list-style-type: none;
            }
            </style>

          1. Alessandro Sperduti, University of Padova 
          2. Andrea Paudice, University of Milan 
          3. Atsushi Miyauchi, CENTAI 
          3. Caterina Graziani, University of Siena 
          3. Clara Holzhüter, University of Kassel 
          3. Corinna Coupette, Max Planck Institute for Informatics
          3. Fabian Jogl, TU Wien 
          3. Florian Seiffarth, University of Bonn 
          3. Franco Scarselli, University of Siena 
          3. Franka Bause, University of Vienna 
          3. Gaurav Rattan, TU Darmstadt 
          3. Giuseppe Alessio D'Inverno, University of Siena 
          3. Ilya Makarov, HSE University Moscow
          3. Ingo Scholtes, University of Würzburg 
          3. Jan Ramon, Inria 
          3. Jefrey Lijffijt, Ghent University
          3. Jilles Vreeken, Helmholtz CISPA 
          3. Jure Leskovec, Stanford 
          3. Lovro Šubelj, University of Ljubljana 
          3. Nils Kriege, University of Vienna 
          3. Sagar Malhotra, TU Wien 
          3. Sebastian Dalleiger, Helmholtz CISPA
          3. Silvia Beddar-Wiesing, University of Kassel 
          3. Sohir Maskey, LMU Munich 
          3. Stefan Neumann, KTH Royal Institute of Technology 
          3. Tamara Drucks, TU Wien 
          3. Till Schulz, University of Bonn 
          3. Veronica Lachi, University of Siena      
          
          
          </div>
 
     

  - block: markdown
    id: mlgkdd23
    content:
        title: MLG@KDD2023
        text: |-
          This year, the International Workshop on Mining and Learning with Graphs is collocated with two conferences. The [ACM SIGKDD Conference on Knowledge Discovery and Data Mining](https://kdd.org/kdd2023/), and the [European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases](https://2023.ecmlpkdd.org/).

          This allows researchers and practitioners from Europe and America to choose a venue that is geographically close and in a suitable time zone.

          Feel free to visit the homepage of this year's sister workshop:
        
          <div style="text-align: center">
          <a href="http://mlgworkshop.org">
          <button style="background-color:#4CAF50;margin-top:2px;margin-bottom:10px;border-radius:4px;font-size:1em;padding:8px 20px;    font-family: "GibsonSemibold", "Helvetica Neue", Helvetica, Arial, sans-serif;float:none !important;text-shadow:0 1px 1px rgba(0,0,0,0.2)">
          19th MLG at KDD
          </button>
          </a>
          </div>



  - block: markdown
    id: history
    content:
        title: Previous Workshops
        text: |-
          <div style="
              display: flex;
              justify-content: center"> 

          * [2023, Long Beach, USA (co-located with KDD)](http://www.mlgworkshop.org/2023)
          * [2022, Grenoble, France (co-located with ECMLPKDD)](https://mlg-europe.github.io/2022/)
          * [2022, Washington, USA (co-located with KDD)](http://www.mlgworkshop.org/2022/)
          * [2020, virtual (co-located with KDD)](http://www.mlgworkshop.org/2020/)
          * [2019, Anchorage, USA (co-located with KDD)](http://www.mlgworkshop.org/2019/)
          * [2018, London, United Kingdom (co-located with KDD)](http://www.mlgworkshop.org/2018/)
          * [2017, Halifax, Nova Scotia, Canada (co-located with KDD)](http://www.mlgworkshop.org/2017/)
          * [2016, San Francisco, USA (co-located with KDD)](http://www.mlgworkshop.org/2016/)
          * [2013, Chicago, USA (co-located with KDD)](http://snap.stanford.edu/mlg2013/)
          * [2012, Edinburgh, Scotland (co-located with ICML)](http://dtai.cs.kuleuven.be/events/mlg2012/)
          * 2011, San Diego, USA (co-located with KDD)
          * [2010, Washington, USA (co-located with KDD)](http://www.cs.umd.edu/mlg2010/)
          * [2009, Leuven, Belgium (co-located with SRL and ILP)](http://dtai.cs.kuleuven.be/ilp-mlg-srl//)
          * [2008, Helsinki, Finland (co-located with ICML)](http://research.ics.aalto.fi/events/MLG08/)
          * 2007, Firenze, Italy
          * 2006, Berlin, Germany (co-located with ECML and PKDD)
          * 2005, Porto, Portugal, October 7, 2005 (co-located with ECML and PKDD)
          * 2004, Pisa, Italy, September 24, 2004 (co-located with ECML and PKDD)
          * [2003, Cavtat-Dubrovnik, Croatia (co-located with ECML and PKDD)](http://www.ar.sanken.osaka-u.ac.jp/MGTS-2003CFP.html)

          </div>
---
