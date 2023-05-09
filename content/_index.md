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

        **Paper Submission Deadline:** June 19th (11:59pm, [AoE](https://time.is/Anywhere_on_Earth)) 2023

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
      show_social: false
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
      show_social: false
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
          
          <div style="margin-left: auto;
            margin-right: auto;
            width: 25%">

          Turin, Italy (all times are [CEST](https://time.is/CEST))
          </div>

          <div style="margin-left: auto;
            margin-right: auto;
            width: 50%">

          All accepted papers will be presented in the poster session.
          </div>


          <div style="margin-left: auto;
            margin-right: auto;
            width: 35%">


          |       | Schedule                             |
          |-------|--------------------------------------|
          | 09:00 | Opening                              |
          | 09:05 | Keynote 1                            |
          | 09:50 | 1st & 2nd oral talks                 |
          | 10:20 | Coffee break                         |
          | 10:50 | Pitch/Introduction talks             |
          | 11:20 | Poster session (Group A)             |
          | 12:30 | Lunch break                          |
          | 13:30 | 3rd & 4th oral talk                  |
          | 14:00 | Keynote 2                            |
          | 15:45 | coffee break with topical discussion |
          | 16:15 | Keynote 3                            |
          | 17:00 | Pitch/Introduction talks             |
          | 17:30 | Poster session (Group B)             |
          | 18:15 | Conclusion & Awards                  |

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
            width: 5%">

          TBC

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

          We welcome many kinds of papers, such as, but not limited to:

          * Novel research papers
          * Demo papers
          * Visionary papers (white papers)
          * Appraisal papers of existing methods and tools (e.g., lessons learned)
          * Relevant work that has been previously published
          * Work that will be presented at the main conference (incl. research, ADS, or journal track; can be submitted in full length ignoring our page limit)

          Authors should clearly indicate in their abstracts the kinds of submissions that the papers belong to, to help reviewers better understand their contributions. All papers will be (single blind) peer reviewed. Submissions must be in PDF, long papers no more than 12 pages long, short papers no more than 8 pages long, formatted according to the standard Springer LNCS style required for ECMLPKDD submissions. Authors can use unlimited additional pages for appendices. The accepted papers will be published on the workshop’s website and will not be considered archival for resubmission purposes. Authors whose papers are accepted to the workshop will have the opportunity to participate in a pitch and poster session, and the best two will also be chosen for oral presentation.

          Please note that at least one author of each accepted paper has to register for the conference.

          Dual Submission Policy: We accept submissions that are currently under review at other venues. However, in this case our page limits apply. Please also check the dual submission policy of the other venue.

          For paper submission, please proceed to our [submission page](https://cmt3.research.microsoft.com/User/Login?ReturnUrl=%2FECMLPKDDworkshop2023%2FSubmission%2FManage).

          Please send enquiries to maximilian.thiessen@tuwien.ac.at.
  
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
      show_social: false
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
          <div style="margin-left: auto;
            margin-right: auto;
            width: 5%"> 

          TBC

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
          <button style="background-color:#a4d61e;margin-top:2px;margin-bottom:10px;border-radius:4px;font-size:1em;padding:8px 20px;    font-family: "GibsonSemibold", "Helvetica Neue", Helvetica, Arial, sans-serif;float:none !important;text-shadow:0 1px 1px rgba(0,0,0,0.2)">
          19th MLG at KDD
          </button>
          </a>
          </div>



  - block: markdown
    id: history
    content:
        title: Previous Workshops
        text: |-
          <div style="margin-left: auto;
            margin-right: auto;
            width: 60%"> 

          * [2023, Washington DC, USA (co-located with KDD)](http://www.mlgworkshop.org/2023)
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
