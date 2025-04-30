---
title: Contact
date: 2025-04-29

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus augue non tempor egestas. Proin nisl nunc, dignissim in accumsan dapibus, auctor ullamcorper neque. Quisque at elit felis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Aenean eget elementum odio. Cras interdum eget risus sit amet aliquet. In volutpat, nisl ut fringilla dignissim, arcu nisl suscipit ante, at accumsan sapien nisl eu eros.
        Intelligent Systems Lab https://www.ntnu.edu/ihb/intelligent-systems-lab
        The lab is located at room L103 at NTNU in Ålesund.

        **Houxiang Zhang**  
        Email: hozh@ntnu.no  
        Phone: +47 7016 1611  

        **Guoyuan Li**  
        Email: guoyuan.li@ntnu.no  
        Phone: +47 7016 1325

       #   email: hozh@ntnu.no
       #   phone: +47 7016 1611
      address:
        street: Larsgårdsvegen 2
        city: Ålesund
        region: Møre og Romsdal
        postcode: '6009'
        country: Norway
        country_code: NO

      oordinates:
        latitude: '62.472278'
        longitude: '6.233797'
      
      directions: |
        Bus stops named "Campus Ålesund"; timetables available at Fram.
        Taxi Services:
        - NorgesTaxi: Phone 08000
        - Ålesund Taxi: Phone +47 70 10 30 00
      office_hours:
        - 'Monday to Friday: 08:00 – 15:00'
      appointment_url: 'https://calendly.com'
     
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
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
