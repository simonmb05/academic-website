---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: false

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: morand-beaulieu.simon@courrier.uqam.ca
  address:
    street: 100 Sherbrooke St W
    city: Montréal
    region: Qc
    postcode: 'H2X 3P2'
    country: Canada
    country_code: CA
  coordinates:
    latitude: '45.51080440790328'
    longitude: '-73.56996950306913'
  directions: 
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/SimonMBeaulieu'

design:
  columns: '2'
---

