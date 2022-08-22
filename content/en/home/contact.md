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

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2796.320776866947!2d-73.5740155!3d45.5036209!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4cc91a46e8d8f69b%3A0xe1f06941072a3209!2s2001%20Av.%20McGill%20College%2C%20Montr%C3%A9al%2C%20QC%20H3A%201G1!5e0!3m2!1sfr!2sca!4v1661192302659!5m2!1sfr!2sca" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
