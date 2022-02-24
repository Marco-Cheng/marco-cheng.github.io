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
  email: marco.cheng712@gmail.com

  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Find me on Twitter
      link: 'https://twitter.com/ZeruiCheng'
    - icon: envelope
      icon_pack: fas
      name: Find me on WeChat by ID Marco_Z_Cheng
      link: 'https://wechat.com'

design:
  columns: '2'
---
