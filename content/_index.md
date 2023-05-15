---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
# - block: features
 #   content:
 #     title: Research Interests<br></br>
 #     items:
  #      - name: 📖 Reproducibility & Metascience
  #        description: '<br></br>'
   #     - name: 🍎 Dietary behaviour change
   #     - name: 📝 Implicit cognition measures 
    #    - name: 🖥️ Experimental Psychology
    #    - name: 🧠 Cognitive Neuroscience
     #   - name: 📊 Data Science using R

  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Tenure Track Fellow
          company: Institute of Population Health, University of Liverpool
          date_start: '2023-04-03'
          date_end: ''
          description: |2-

          <p-card>• Designing and testing population-level interventions with a focus on nutrition-related health (proof-of-concept and semi-naturalistic experiments)</p-card>
          <p-card>• Reviewing and evaluating public policy associated with diet and obesity with attention to current health inequalities</p-card>
          <p-card>• Teaching and project supervision for BSc (Hons) Psychology </p-card>
        - title: Postdoctoral Research Associate 
          company: CUBRIC, Cardiff University
          date_start: '2021-10-01'
          date_end: ''
          description: |2-
          
              <p-card>Metascience projects (Part-time since April 2023):</p-card>
        
               <p-card>• Building tools for the implementation of [TOP guidelines](https://www.cos.io/initiatives/top-guidelines) in academic journals </p-card>
               
               <p-card> • Conducting meta-scientific research for TOP guidelines and Registered Reports</p-card>
        - title: Postdoctoral Research Fellow (ESRC)
          company: CUBRIC, Cardiff University
          date_start: '2020-10-01'
          date_end: '2021-09-01'
          description:  |2-
               <p-card> ESRC Postdoctoral fellowship [Reproducibility in health intervention research and beyond: addressing the challenges and developing innovative solutions](https://gtr.ukri.org/projects?ref=ES%2FV011030%2F1#/tabOverview) (£126,071) </p>
        - title: Postdoctoral Researcher
          company: CUBRIC, Cardiff University
          date_start: '2019-11-01'
          date_end: '2020-09-01'
        - title: Research Assistant (Part-time)
          company: CUBRIC, Cardiff University
          date_start: '2019-11-01'
          date_end: '2020-09-01'
          description: |2-
               <p-card> Contributed to the database for the [Restrain app](https://www.cardiff.ac.uk/cardiff-cognition-and-neurostimulation-group/restrain-app) </p>
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
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
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
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
# - block: features
 #   content:
  #    title: Skills
   #   items:
    #    - name: R
     #     description: Data preprocessing, visualisation and statistical analyses
      #    icon: r-project
       #   icon_pack: fab
        #- name: Statistics
         # description: 100%
          #icon: chart-line
          #icon_pack: fas
        #- name: Photography
         # description: 10%
          #icon: camera-retro
          #icon_pack: fas
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: l.tzavella@liverpool.ac.uk
      appointment_url: 'https://calendly.com/tzavellaloukia'
      address:
        street: Eleanor Rathbone Building, Bedford Street South
        city: Liverpool
        region: England
        postcode: 'L69 7ZA'
        country: United Kingdom
        country_code: UK
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
