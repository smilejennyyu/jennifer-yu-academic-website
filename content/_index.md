---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 4
      # Filter on criteria
      filters:
        folders:
          - news
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
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 2
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
    id: recent
    count: 3
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
        - name: NLP
          tag: NLP
        - name: Time Series
          tag: Time Series
        - name: Ongoing
          tag: Ongoing
        - name: Other
          tag: Model Compression
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  - block: experience
    id: experiences
    content:
      title: Experiences
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      count: 5
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Intern
          company: Enable Medicine
          company_url: 'https://www.enablemedicine.com/'
          company_logo: "enable"
          location: Menlo Park, California, USA
          date_start: '2023-05-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Deep learning R&D 
              * Medical imaging analysis
        - title: Research Student
          company: Vector Institute - Goldenberg Lab
          company_url: 'https://goldenberglab.ca/'
          company_logo: vector-test
          location: Toronto, Ontario, Canada
          date_start: '2022-05-01'
          date_end: ''
          description: |2-
              * Designed and implemented a novel dynamic change point detection method with better performance and interpretability
              * Developing interpretable time-series forecasting models for pregnancy delivery date prediction
              * Exploring individualized delivery readiness using machine learning methods
        - title: Research Student (Co-op)
          company: Ontario Institute for Cancer Research - Pai Lab
          company_url: 'https://pailab.oicr.on.ca/'
          company_logo: oicr
          location: Toronto, Ontario, Canada
          date_start: '2021-05-01'
          date_end: '2021-08-30'
          description: |2-
              * Developed a deep-learning patient classifier with an accuracy of 88% using graph attention networks to predict clinical outcomes of patients with cancer
              * Improved model computational efficiency by ~50% compared to existing algorithms 

        - title: Undergraduate Research Assistant
          company: University of Waterloo - Wireless Sensors and Devices Lab
          company_url: 'https://uwaterloo.ca/wireless-sensors-and-devices-lab/'
          company_logo: uwaterloo
          location: Waterloo, Ontario, Canada
          date_start: '2020-07-01'
          date_end: '2020-12-20'
          description: |2-
              * Built an ML model with high precision and recall for in-car occupant detection using 4D MIMO radar 
              * Designed an ML data pipeline for multi-label classification with big data, including data pre-processing, model training & testing and performance evaluation
              * Analyzed and benchmarked different neural network architectures


    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_start: '2022-09-01'
          date_end: '2023-08-31'
          organization: Vector Institute
          description: 'The Vector Scholarship in Artificial Intelligence awarded to top students pursuing AI master’s in Ontario university, these merit-based entrance awards recognize exceptional candidates pursuing a master’s program recognized by the Vector Institute or candidates who are following an individualized study path that is demonstrably AI-focused.'
          title: Vector Scholarship in Artificial Intelligence ($17,500)
        - date_start: '2022-09-01'
          date_end: '2023-08-31'
          organization: Province of Ontario, University of Toronto
          description: 'The Ontario Graduate Scholarship (OGS) program encourages excellence in graduate studies at publicly-assisted universities in Ontario. Since 1975, the OGS program has been providing merit-based scholarships to Ontario’s best graduate students in all disciplines of academic study.'
          title: Ontario Graduate Scholarship ($15,000)
        - date_start: '2021-05-01'
          date_end: '2021-08-31'
          organization: Province of Ontario, University of Toronto
          description: 'The Ontario Graduate Scholarship (OGS) program encourages excellence in graduate studies at publicly-assisted universities in Ontario. Since 1975, the OGS program has been providing merit-based scholarships to Ontario’s best graduate students in all disciplines of academic study.'
          title: BioTalent Canada Work Placement Program Funding ($7,000)
        - date_start: '2020-09-01'
          date_end: '2022-04-30'
          organization: NSERC, CIHR, SSHRC
          description: 'The BioTalent Canada Work Placement Program Funding aims to fund high-achieving students in science, technology, engineering, mathematics (STEM), and business fields, providing them with exclusive opportunities to gain practical experience through funded work placements with esteemed employers.'
          title: NSERC Undergraduate Student Research Award ($6,000 × 3)
        - date_start: '2019-09-01'
          date_end: '2020-12-20'
          organization: University of Waterloo
          description: "The President's Research Award is a $1500 award available to eligible full-time undergraduate students who were recipients of the President’s Scholarship of Distinction and are interested in pursuing an on-campus research experience, under the supervision of a University of Waterloo researcher."
          title: President’s Research Award  ($1,500 × 2)
        - date_start: '2017-09-01'
          date_end: '2018-04-30'
          organization: University of Waterloo
          description: "The President's Scholarship of Distinction is an award given to students with 95+ admission average."
          title: President’s Scholarship of Distinction ($2,000)
        # - certificate_url: https://www.edx.org
        #   date_end: ''
        #   date_start: '2021-01-01'
        #   description: Formulated informed blockchain models, hypotheses, and use cases.
        #   organization: edX
        #   organization_url: https://www.edx.org
        #   title: Blockchain Fundamentals
        #   url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    design:
      columns: '2'
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     text: |-
  #       If you're interested in exploring a potential collaboration with me or organizing academic/industrial/educational events, please don't hesitate to reach out! I am always open to fresh perspectives and innovative partnerships.
  #     # Contact (add or remove contact options as necessary)
  #     email: test@example.org
  #     phone: 888 888 88 88
  #     appointment_url: 'https://calendly.com'
  #     address:
  #       street: 450 Serra Mall
  #       city: Stanford
  #       region: CA
  #       postcode: '94305'
  #       country: United States
  #       country_code: US
  #     directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
  #     contact_links:
  #       - icon: twitter
  #         icon_pack: fab
  #         name: DM Me
  #         link: 'https://twitter.com/Twitter'
  #       - icon: skype
  #         icon_pack: fab
  #         name: Skype Me
  #         link: 'skype:echo123?call'
  #       - icon: video
  #         icon_pack: fas
  #         name: Zoom Me
  #         link: 'https://zoom.com'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false
  #   design:
  #     columns: '2'
---
