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
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
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
    design:
      columns: '2'
---



