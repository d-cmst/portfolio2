---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact Me
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: formspree
    formspree:
      id: xpznnpzk
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: d-cmst@gmail.com
  # phone: 888 888 88 88
  # address:
  #   street: 450 Serra Mall
  #   city: Stanford
  #   region: CA
  #   postcode: '94305'
  #   country: United States
  #   country_code: US
  # coordinates:
  #   latitude: '37.4275'
  #   longitude: '-122.1697'
  # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  # office_hours:
  #   - 'Monday 10:00 to 13:00'
  #   - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com/d-cmst'
  contact_links:
    - icon: shipping-fast
      icon_pack: fas
      name: Sent me an email (Reply Guaranteed)
      link: 'https://www.mypublicinbox.com/d-cmst'
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/d-cmst'

design:
  columns: '2'
---
