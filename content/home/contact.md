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
  email: 3190105622@zju.edu.cn
  phone: +86 19817861847
  address:
    street: Lingyin Street
    city: Hangzhou
    region: Zhejiang
    postcode: '310013'
    country: China
    country_code: CN
  directions: No.32 Building
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'

design:
  columns: '2'
---
