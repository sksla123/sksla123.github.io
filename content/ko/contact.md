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
          <script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
          <link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
          <div id="map"></div>
          <script>
            // Leaflet 초기화
            var map = L.map('map').setView({lon: 35.84601324617979, lat: 127.13444961966684}, 13);
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
            L.marker({lon: 35.84601324617979, lat: 127.13444961966684}).bindPopup('전북대학교 공학대학, 7호관 601호').addTo(map);
          </script>
          <style>
            #map {
              /* 지도의 크기를 설정 */
              width: 100%;
              height: 100%;
              position: absolute;
            }
          </style>
---