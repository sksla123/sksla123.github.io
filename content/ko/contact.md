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
              center: new kakao.maps.LatLng(35.84601324617979, 127.13444961966684),
              level: 3
            };
            var map = new kakao.maps.Map(container, options);
            // 마커가 표시될 위치입니다 
            var markerPosition  = new kakao.maps.LatLng(35.84601324617979, 127.13444961966684); 

            // 마커를 생성합니다
            var marker = new kakao.maps.Marker({
                position: markerPosition
            });

            // 마커가 지도 위에 표시되도록 설정합니다
            marker.setMap(map);
          </script>
---