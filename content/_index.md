---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Summary
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: skills
  #   content:
  #     title: Skills
  #     text: ''
  #     # Choose a user to display skills from (a folder name within `content/authors/`)
  #     username: admin
    design:
      columns: '1'
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
        - title: Analytics Engineer
          company: Gridwise
          company_url: 'https://gridwise.io'
          # company_logo: org-gc
          location: USA - Remote
          date_start: '2024-09-23'
          date_end: ''
        - title: Senior Business Intelligence Developer
          company: Greenpeace International
          company_url: 'https://www.greenpeace.org/international/'
          location: The Netherlands - Remote
          date_start: '2023-06-01'
          date_end: '2024-09-16'
          # description: |2-
          #     Responsibilities include:

          #     * Analysing
          #     * Modelling
          #     * Deploying
        - title: Software Engineer
          company: OnAgri
          company_url: ''
          # company_logo: org-x
          location: Brazil - Remote
          date_start: '2023-08-01'
          date_end: '2024-08-30'
          # description: Taught electronic engineering and researched semiconductor physics.
        - title: Data Scientist
          company: Stockholm Environment Institute (SEI)
          company_url: 'https://www.sei.org'
          # company_logo: org-x
          location: Stockholm (Sweden) - Hybrid
          date_start: '2021-05-31'
          date_end: '2023-05-18'
          # description: Taught electronic engineering and researched semiconductor physics.
        - title: Geospatial Data Analyst
          company: Imaflora
          company_url: 'https://www.imaflora.org'
          # company_logo: org-x
          location: Brazil - In-person
          date_start: '2018-06-18'
          date_end: '2021-05-07'
          # description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Certificates'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.credly.com/badges/64c1e6a1-6ab3-439b-ba75-52849b005870
          date_end: ''
          date_start: '2024-07-12'
          description: ''
          icon: tableau
          organization: Tableau
          organization_url: https://www.tableau.com/
          title: Tableau Desktop Specialist
          url: ''
        - certificate_url: https://www.credly.com/badges/1ddbb74c-9730-43c9-bbb8-1f6534116856
          date_end: ''
          date_start: '2023-09-09'
          description: ''
          icon: aws
          organization: AWS
          organization_url: https://aws.amazon.com/
          title: AWS Certified Cloud Practitioner
          url: ''
        - certificate_url: https://credentials.getdbt.com/4fbddf11-3285-41d9-9250-5d3687701c30#gs.5xkbh3
          date_end: ''
          date_start: '2023-06-01'
          description: ''
          icon: dbt
          organization: dbt Labs
          organization_url: https://getdbt.com/
          title: dbt Fundamentals
          url: ''
        - certificate_url: https://drive.google.com/file/d/13klHLHzOoAUnivQUQz6iPHnZrIuXyjHk/view?usp=sharing
          # date_end: '2020-12-21'
          date_start: '2022-09-22'
          description: '73 hours'
          icon: datacamp
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: Data Engineering 
          url: ''
        - certificate_url: https://drive.google.com/file/d/1TgvdIAt9so0HaiWghSS-QTpX57NotMbU/view?usp=sharing
          # date_end: '2020-12-21'
          date_start: '2023-02-11'
          description: '108 out of 120'
          # icon: datacamp
          organization: ETS
          organization_url: https://www.ets.org/toefl.html
          title: TOEFL iBT
          url: ''
    design:
      columns: '2'
  # - block: collection
  #   id: blog
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
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
        - name: Software Engineering
          tag: Software Engineering
        - name: Analytics Engineering
          tag: Analytics Engineering
        - name: Business Intelligence
          tag: Business Intelligence          
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
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
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
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
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      # subtitle:
      # text: |-
      #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # # Contact (add or remove contact options as necessary)
      # email: tomas.jpeg@gmail.com
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '-22.7261602'
        longitude: '-47.6454611'  
        zoom: 6
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
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
