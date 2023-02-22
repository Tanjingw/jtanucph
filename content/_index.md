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
    design:
      columns: '2'
  - block: experience
    id: edu
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Postgraduate Student
          company: University of Copenhagen
          company_url: 'https://www.ku.dk/english/'
          company_logo: org-gc
          location: Copenhagen, Denmark
          date_start: '2022-09-01'
          date_end: ''
          description: 
        - title: Bachelor of Economics
          company: Henan University
          company_url: 'https://iao.henu.edu.cn/yw/Home.htm'
          company_logo: org-x
          location: Kaifeng, China
          date_start: '2018-09-01'
          date_end: '2022-06-01'
          description: 
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Research
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
    id: pub
    content:
      title: Publication
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: tjw@henu.edu.cn
      directions: Øster Farimagsgade 5, Copenhagen, DK-1353, Denmark
      contact_links:
    design:
      columns: '2'
---
