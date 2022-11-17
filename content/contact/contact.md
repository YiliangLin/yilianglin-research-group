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

  email: yilianglinzju@gmail.com
  phone: 888 888 88 88
  address:
    street: Blk E5 02-19, 4 Engineering Drive 4
    city: Singapore
    region: Singapore
    postcode: '117585'
    country: Singapore
    country_code: SG
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Blk E5 02-19, 4 Engineering Drive 4
  office_hours:
    - 'Monday to Friday 9:00 to 18:00'
  appointment_url: 'https://calendly.com'
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
