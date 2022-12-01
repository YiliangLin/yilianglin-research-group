---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: y.lin@nus.edu.sg
  phone: 65168405
  address:
    street: Blk E5 03-04, 4 Engineering Drive 4
    city: Singapore
    region: Singapore
    postcode: '117585'
    country: Singapore
    country_code: SG
  coordinates:
    latitude: '1.298126'
    longitude: '103.772206'
    
  #contact_links:
  #  - icon: comments
  #    icon_pack: fas
  #    name: Discuss on Forum
  #    link: 'https://discourse.gohugo.io'

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
  columns: '1'
---
