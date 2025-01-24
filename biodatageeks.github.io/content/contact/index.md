---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      #text: |-
#        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus augue non tempor egestas. Proin nisl nunc, dignissim in accumsan dapibus, auctor ullamcorper neque. Quisque at elit felis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Aenean eget elementum odio. Cras interdum eget risus sit amet aliquet. In volutpat, nisl ut fringilla dignissim, arcu nisl suscipit ante, at accumsan sapien nisl eu eros.
      email: team@biodatageeks.org
      # phone: 888 888 88 88
      address:
        street: Nowowiejska 15/19
        city: Warsaw
       # region: Masovian
        postcode: '00-665 '
        country: Poland
        country_code: Pl
      coordinates:
        latitude: '52.2207'
        longitude: '21.0065'
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday - Friday 9:00 to 17:00'
      #  - 'Wednesda 09:00 to 10:00'
      #appointment_url: 'https://calendly.com'
      # contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
      #contact_links:
       # - icon: github
        #  icon_pack: fab
         # name: GitHub
          #link: 'https://github.com/biodatageeks/biodatageeks.github.io'
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

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
