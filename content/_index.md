---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: lchetot

  - block: experience
    content:
      title: Experience
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Assistant Professor
          company: Maracas Team @ INRIA / CITI Lab. @ INSA Lyon
          company_url: ''
          company_logo: 
          location: Villeurbanne (France)
          date_start: '2022-09-01'
          date_end: '2024-08-31'
        - title: PhD Candidate
          company: Maracas Team @ INRIA / CITI Lab. @ INSA Lyon
          company_url: ''
          company_logo: 
          location: Villeurbanne (France)
          date_start: '2018-10-01'
          date_end: '2022-07-07'
        - title: Research Intern
          company: Maracas Team @ INRIA / CITI Lab. @ INSA Lyon
          company_url: ''
          company_logo: 
          location: Villeurbanne (France)
          date_start: '2018-02-01'
          date_end: '2018-08-01'
        - title: Research Intern
          company: Thales
          company_url: ''
          company_logo: 
          location: Gennevilliers (France)
          date_start: '2017-04-01'
          date_end: '2017-07-01'
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

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text:
      # Contact (add or remove contact options as necessary)
      email: lelio.chetot@insa-lyon.fr
      address:
        street: 6 Avenue des Arts
        city: Villeurbanne
        region:
        postcode: '69100'
        country: France
        country_code: FR
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '45.7835492663557'
        longitude: '4.87280741461803'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
