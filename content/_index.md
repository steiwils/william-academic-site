---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: features
  content:
    items:
    - description: 
      icon: r-project
      icon_pack: fab
      name: R
    - description: 
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: 
      icon: python
      icon_pack: fab
      name: Python
    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Chr. Hansen
      company_logo:
      company_url: "https://www.linkedin.com/company/chr-hansen-as/"
      date_end: ""
      date_start: "2017-12-04"
      description: |2-
          Responsibilities include:

          * Building analytical tools using R and Power BI
          * Communication with internal and external customers
          * Collaborating on cross-functional advanced analytical projects
      location: Wisconsin
      title: Senior Data Analyst
    title: Experience
  design:
    columns: "2"
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: https://opencv.org/
      date_end: ""
      date_start: "2023-09-01"
      description: ""
      organization: OpenCV
      organization_url: https://opencv.org/
      title: Mastering OpenCV with Python
      url: ""
    - certificate_url: https://coursera.org/share/94ea713de84190ec3281441d276055b0
      date_end: ""
      date_start: "2020-09-21"
      description: "Linear Algebra"
      organization: Coursera
      organization_url: https://coursera.org
      title: Mathematics for Machine Learning 
      url: ""
    subtitle: null
    title: Accomplish&shy;ments
  design:
    columns: "2"
- block: collection
  content:
    count: 3
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: contact
  content:
    address:
      city: Milwaukee
      country: United States
      country_code: US
      postcode: 
      region: WI
      street: 
    autolink: true
    contact_links:
    directions: If you're in the Milwaukee area, invite me for a coffee or beer.
    email: william.s.steinke@gmail.com
    form:
      formspree:
        id: null
      netlify:
        captcha: true
      provider: netlify
    subtitle: null
    text: If you would like to contact with me for collaborations or inquires, please fill out the section below.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
