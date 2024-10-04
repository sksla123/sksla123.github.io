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
          <script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
          <link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
          <style>
            html, body {
              height: 100%;
              padding: 0;
              margin: 0;
            }
            #map {
              /* 지도의 크기를 설정 */
              width: 100%;
              height: 100%;
            }
          </style>
          <div id="map"></div>
          <script>
            // Leaflet 초기화
            var map = L.map('map').setView({lon: 127.766, lat: 36.355}, 13);
            // 최대 범위 지정
            map.setMaxBounds([[32, 123], [44, 132.5]]);
            // '오픈스트리트맵 한국'에서 서비스하는 '군사 시설 없는 오픈스트리트맵 지도 타일'을 삽입
            L.tileLayer('https://tiles.osm.kr/hot/{z}/{x}/{y}.png', {
              maxZoom: 19,
              attribution: '&copy; <a href="https://openstreetmap.org/copyright">OpenStreetMap 기여자</a>'
            }).addTo(map);
            // 축척 막대를 지도 왼쪽 하단에 노출 
            L.control.scale({imperial: true, metric: true}).addTo(map);
            // 마커를 지도에 추가
            L.marker({lon: 127.766, lat: 36.355}).bindPopup('대한민국의 중심지, 장연리마을').addTo(map);
          </script>
---