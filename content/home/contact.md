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
  email: zoeyang@cuhk.edu.hk
  phone: 852 3943 4033
  address:
    street: 12 Chak Cheung Street
    city: Shatin, N.T.
    country: Hong Kong
    country_code: HK
  directions: Room 726, 7/F, Cheng Yu Tung Building

design:
  columns: '2'
---
