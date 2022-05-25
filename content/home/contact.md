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
      captcha: true

  # Contact details (edit or remove options as required)
  email: s1687781@ed.ac.uk
  address:
    street: James Clerk Maxwell Building, Peter Guthrie Tait Road
    city: Edinburgh
    postcode: EH9 3FD
    country: United Kingdom
    country_code: UK
  coordinates:
    latitude: '55.9214'
    longitude: '3.1733'
  <!--- directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00' 
  appointment_url: 'https://calendly.com' --->
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    <!--- - icon: video
    #  icon_pack: fas
    #  name: Zoom Me
    #  link: 'https://zoom.com' --->

design:
  columns: '2'
---
