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
        - title: Postdoctoral Fellow
          company: LS2PR @ CEA Leti
          company_url: 'https://www.leti-cea.com/cea-tech/leti/english'
          company_logo: cea_red
          location: Grenoble (France)
          date_start: '2024-10-04'
          date_end: '2026'
        - title: Assistant Professor
          company: Maracas Team @ INRIA / CITI Lab. @ INSA Lyon
          company_url: 'https://team.inria.fr/maracas/'
          company_logo: insa_color
          location: Villeurbanne (France)
          date_start: '2022-09-01'
          date_end: '2024-08-31'
        - title: PhD Candidate
          company: Maracas Team @ INRIA / CITI Lab. @ INSA Lyon
          company_url: 'https://team.inria.fr/maracas/'
          company_logo: inria_red
          location: Villeurbanne (France)
          date_start: '2018-10-01'
          date_end: '2022-07-07'
        - title: Research Intern
          company: Maracas Team @ INRIA / CITI Lab. @ INSA Lyon
          company_url: 'https://www.citi-lab.fr/'
          company_logo: citi_color
          location: Villeurbanne (France)
          date_start: '2018-02-01'
          date_end: '2018-08-01'
        - title: Research Intern
          company: Thales SIX GTS
          company_url: 'https://www.thalesgroup.com/en'
          company_logo: thales
          location: Gennevilliers (France)
          date_start: '2017-04-01'
          date_end: '2017-07-01'
    design:
        columns: '1'

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
