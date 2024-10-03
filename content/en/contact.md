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
---