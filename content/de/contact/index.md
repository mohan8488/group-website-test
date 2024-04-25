---
title: Kontakt
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Kontakt
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus augue non tempor egestas. Proin nisl nunc, dignissim in accumsan dapibus, auctor ullamcorper neque. Quisque at elit felis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Aenean eget elementum odio. Cras interdum eget risus sit amet aliquet. In volutpat, nisl ut fringilla dignissim, arcu nisl suscipit ante, at accumsan sapien nisl eu eros.
      email: martina.benedikt@univie.ac.at
      phone: +43-1-4277-73251
      address:
        street: Währinger Straße 38-42
        Room: 3143C
        city: Wien
        region: AT
        postcode: '1090'
        country: Österreich
        country_code: AT
      coordinates:
        latitude: '648.8583'
        longitude: '2.2923'
      directions: Gehen Sie durch das Tor der Boltzmanngasse 1 und rufen Sie die Kontaktnummer an. Ein Mitglied der Gruppe wird Sie abholen.
      office_hours:
        - 'Monday to Friday 9:00 to 17:00'
      #  - 'Wednesday 09:00 to 10:00'
      appointment_url: 'https://calendly.com'
      contact_links:
        - icon: x-twitter
          icon_pack: fab
          name: DM me
          link: 'https://twitter.com/cerbino'
    
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
