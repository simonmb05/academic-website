---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

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
  email: simon.morand-beaulieu@mcgill.ca
  address:
    street: 2001 McGill College Avenue
    city: Montréal
    region: Qc
    postcode: 'H3A 1G1'
    country: Canada
    country_code: CA
  coordinates:
    latitude: '45.50374121118067'
    longitude: '-73.57398331349235'
  directions: Office 1566
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/SimonMBeaulieu'

design:
  columns: '2'
---

