---
# Leave the homepage title empty to use the site title
title: Qi Zhang's academic home
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: news
    content:
      title: News
      count: 6
      filters:
        folders:
          - news
    design:
      columns: '2'
      view: compact
  - block: collection
    id: featured
    content:
      title: Selected Publications
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
      title: Projects & Code
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
        - name: SLAM
          tag: SLAM
        - name: Demo
          tag: Demo
    design:
      columns: '1'
      view: showcase
      flip_alt_rows: false
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        I welcome exchanges and collaborations with fellow scholars. Undergraduate students are also welcome to work together on projects. Please feel free to contact me.
      # Contact (add or remove contact options as necessary)
      email: q.zhang2@uva.nl
      office_hours:
        - '8:00 to 18:00'
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
