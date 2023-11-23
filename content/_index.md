---
# Leave the homepage title empty to use the site title
title: ''
date: 2023-11-23
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '2'
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Senior Data Scientist
          company: Children's Medical Research Institute
          company_url: 'https://www.cmrijeansforgenes.org.au/'
          company_logo: cmri
          location: Westmead
          date_start: '2023-02-01'
          date_end: ''
          description: |2-
              
              * Designed and built multi-view VAE models customised for multi-omic data integration
              * Performed various machine learning analyses on omics data

        - title: Data Scientist
          company: Children's Medical Research Institute
          company_url: 'https://www.cmrijeansforgenes.org.au/'
          company_logo: cmri
          location: Westmead
          date_start: '2019-01-07'
          date_end: '2020-02-28'
          description: |2-
              
              * Built pipelines using existing models for single-cell RNA-seq analysis in mouse developmental biology
              * Built deep learning models for live-cell imaging data analysis
              
        - title: Analyst Programmer
          company: Goldman Sachs
          company_url: 'https://www.goldmansachs.com/'
          company_logo: gs
          location: Melbourne
          date_start: '2014-11-10'
          date_end: '2017-12-31'
          description: |2-
              
              * Communicated with business stakeholders and liaised regarding project scope with ongoing updates
              * Designed/developed/tested/deployed system solutions specialised in Goldman Sachs Electronic Trading (GSET)business flow
              * Provided production support and maitained the health of testing environment
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
---
