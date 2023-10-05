---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: R
          icon: r-project
          icon_pack: fab
        - name: Stata
          icon: chart-line
          icon_pack: fas
        - name: LaTeX
          icon: file
          icon_pack: fas
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
      - title: Director for Financial Policy Analysis
          company: Ministry of Finance and Public Credit of Mexico
          company_url: ''
          company_logo: org-x
          location: Mexico City
          date_start: '2017-03-01'
          date_end: '2018-08-15'
      - title: Economic Advisor to the Undersecretary of Finance
          company: Ministry of Finance and Public Credit of Mexico
          company_url: ''
          company_logo: org-x
          location: Mexico City
          date_start: '2014-01-01'
          date_end: '2017-02-28
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: sascenciopastora@g.harvard.edu
      phone: 617 530 0430
      address:
        street: 1730 Cambridge St
        city: Cambridge
        region: MA
        postcode: '02138'
        country: United States
        country_code: US
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



