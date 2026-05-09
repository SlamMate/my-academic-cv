---
# Leave the homepage title empty to use the site title
title: Qi Zhang's academic home
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: news
    content:
      title: Recent News
      count: 5
      filters:
        folders:
          - news
    design:
      columns: '1'
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
      columns: '1'
      view: citation
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '1'
      view: citation
  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
    design:
      columns: '1'
      view: compact
  - block: collection
    id: talks
    content:
      title: Talks & Events
      filters:
        folders:
          - event
    design:
      columns: '1'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        I welcome research discussions and collaboration opportunities. Please feel free to reach out by email.
      # Contact (add or remove contact options as necessary)
      email: q.zhang2@uva.nl
      office_hours:
        - '09:00-18:00'
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
