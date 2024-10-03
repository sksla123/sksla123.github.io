---
title: 'Contact Me'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: markdown
    content:
        title: '연락 방법'
        subtitle: ''
        text: |-
          알아서 연락하세연
  - block: markdown
    content:
        title: '지도'
        subtitle: ''
        text: |-
          <div id="map" style="width:500px;height:400px;"></div>
          <script type="text/javascript" src="//dapi.kakao.com/v2/maps/sdk.js?appkey=d01cc5d7b082a1617737b414ef005921"></script>
          <script>
            var container = document.getElementById('map');
            var options = {
              center: new kakao.maps.LatLng(33.450701, 126.570667),
              level: 3
            };
            var map = new kakao.maps.Map(container, options);
          </script>
  - block: contact
    content:
      title: Contact
      text: |-
        <br> <span style="font-size:95%">전북대학교 의료 AI 및 계산 수학 연구실 (Macs)의 학부연구생/석사 position에 관심 있으시면 아래로 연락주시면 감사드리겠습니다.</span> <br>
      email: ksl(at)jbnu.ac.kr
      phone: +82-63-270-2406
      address:
        street: 전북대학교 공과대학 7호관 626호
        city: 전주시
        region: 전라북도
        postcode: '54896'
        country: 대한민국
        country_code: KO
      coordinates:
        latitude: '35.84601324617979'
        longitude: '127.13444961966684'
      directions: 
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: true
    design:
      columns: '3'
---