---
title: Contact
# date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact Me
      email: pjy010608@naver.com
      phone: 010-8860-6073
      
  - block: contact
    content:
      title: Directions
      address:
        street: Data Mining Lab, Room 601, Building 7, College of Engineering, Jeonbuk National University
        city: Jeonju-si
        region: Jeonbuk-do
        postcode: '54896'
        country: Republic of Korea
        country_code: KO
      coordinates:
        latitude: '35.84601324617979'
        longitude: '127.13444961966684'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '1'
  
  # - block: buttons
  #   content:
  #     buttons:
  #       - title: 메세지 보내기
  #         icon: paper-plane
  #         icon_pack: fas
  #         url: _contact
  
  - block: slider
    content:
      title: button
      slides:
      - title: 'Send a Message'
        content: 'You can send a message by clicking the button below.'
        align: center
        link:
          icon: paper-plane
          icon_pack: fas
          text: Message
          url: /en/_contact    
        background:
          color: '#999'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '300px'
      is_fullscreen: false

  # - block: contact
  #   content:
  #     title: 연락하기
  #     text: |-
  #       궁금한 것이 있으시면 언제든지 연락 주세요.
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false  
  #   design:
  #     columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: contact.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen
---
