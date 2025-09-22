---
# Leave the homepage title empty to use the site title
title: 
# date: 2022-10-24
type: landing

sections:
  - block: markdown
    id: intro
    content:
      title: | 
        # Welcome to the MANIFOLD Lab
      image:
        filename: 'MANIFOLD_logo_full.jpg'
      text: |

        <center>{{< figure library="true" src="MANIFOLD_logo_full.png" title="" alt="MANIFOLD logo" width=600 >}}</center>

        ## {{< icon name="question-circle" pack="far" >}} About the lab
        Welcome to the website of the Machine-learning Artificial Intelligence Neuro Imaging Focusing on Longevity & Dementia (MANIFOLD) Laboratory. We are based at University College London, part of the [UCL Hawkes Institute](https://www.ucl.ac.uk/hawkes-institute), formerly the Centre for Medical Image Computing (CMIC), and the [Dementia Research Centre (DRC)](https://www.ucl.ac.uk/drc/) at the Queen Square Institute of Neurology.

        ## {{< icon name="rocket" pack="fas" >}} Mission Statement
        Our goal is to further our understanding of how the brain ages and how this affects risk of cognitive decline, neurodegenerative diseases and dementia. We do this using advanced statistics, machine learning and AI methods to analyse neuroimaging data, alongside genetic, cognitive, clinical, biological and behavioural information – taking a big-data science approach to help translate computational methods into the clinic for people with age-associated cognitive decline, dementia and related conditions.

        <center>{{< figure library="true" text-align="center" src="lab_beliefs_poster.png" title="" alt="Lab beliefs" width=450 >}}</center>

        <center>{{< figure library="true" src="Hawkes-DRC_logo.png" title="" alt="UCL Hawkes DRC logos" width=600 >}}</center>

    design:
      columns: '1'

  - block: people
    id: people
    content:
      title: Meet the Team
      user_groups:
          - Principal Investigators
          - Researchers
          - PhD Students
          - Alumni
          - Visitors
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: true
      show_role: true
      show_social: true

  - block: features
    content:
      title: Lab expertise
      items:
      - name: Statistics
        icon_pack: fas
        icon: chart-line
      - name: Machine Learning
        icon_pack: fas
        icon: cogs
      - name: Artificial Intelligence
        icon_pack: fas
        icon: robot
      - name: Dementia
        icon_pack: fas
        icon: brain
      - name: Ageing
        icon_pack: fas
        icon: stopwatch
      - name: Imaging
        icon_pack: fas
        icon: magnet
      
  - block: collection
    id: post
    content:
      title: News
      text: ""
      count: 3
      filters:
        folders:
          - post
    sort_by: 'Date'
    sort_ascending: false
    design:
      view: card
      columns: '2'

  - block: portfolio
    id: project
    content:
      title: Projects
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Machine Learning
          tag: Machine Learning
        - name: Interpretable AI
          tag: Interpretable AI
        - name: Neuroimaging
          tag: Neuroimaging
        - name: Neurodevelopment
          tag: Neurodevelopment
        - name: Brain Age
          tag: Brain Age
        - name: Dementia
          tag: Dementia
        - name: UK Biobank
          tag: UK Biobank
    design: 
      columns: '2'
      view: masonry
      flip_alt_rows: false
      
      
  - block: collection
    id: publication
    content:
      title: Recent Publications
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '2'

  - block: tag_cloud
    content: 
      title: Popular topics
    design:
      columns: '2'

  - block: contact
    id: contact
    content: 
      title: Contact
      text: |
        <center>{{< figure library="true" src="MANIFOLD_logo_small_v3.png" title="" alt="MANIFOLD logo" width=200 >}}</center>
      email: james.cole@ucl.ac.uk
      #phone: 888 888 88 88
      address:
        street: 90 High Holborn
        city: London
        region: ''
        postcode: 'WC1V 6LJ'
        country: United Kingdom
        country_code: UK
      coordinates:
        latitude: '51.518'
        longitude: '-0.118'
      directions: 1st floor UCL Engineering
      office_hours: ''
      # appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'

---
