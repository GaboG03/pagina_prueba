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
  email: gabo_granda@hotmail.com
  phone: +593 998309526
  address:
    street: Chimborazo O3 6 - 32 y Bahía 
    city: Quito
    region: Pichincha
    postcode: '593'
    country: Ecuador
    country_code: EC
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'

design:
  columns: '2'
---
