---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    content:
      title: <br> Biography<br><br>
      username: "admin"  # 여기에서 admin을 지정
    design:
      font:
        color: white
      background:
        image: 
          filename: stacked-peaks_lightblue.svg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
  
  - block: markdown
    content:
      title:
      text:

  - block: slider
    content:
      slides:
      - title: 새내기 개발자
        content: 작은 코드로 큰 변화를 만들며, 기술로 세상을 혁신하는 개발자가 되겠습니다.
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: 자연어 처리
        content: 언어의 경계를 허물고, 사람과 기계의 소통을 자연스럽게 이어주는 NLP 전문가를 꿈꿉니다.
        align: center
        background:
          image:
            filename: NLP.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: 정보 검색
        content: 방대한 데이터 속에서 가치를 찾아내는, 스마트한 정보 탐색의 선두주자가 되겠습니다.
        align: center
        background:
          image:
            filename: IR.jpeg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        # link:
        #   icon: graduation-cap
        #   icon_pack: fas
        #   text: Join Us
        #   url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 2000
      
  - block: collection
    content:
      title: My Projects<br><br>
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
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
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
