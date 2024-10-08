---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: bio
    content:
      title: Biography
      username: "admin"  # 여기에서 admin을 지정
    design:
      font:
        color: white
      background:
        image: 
          filename: stacked-peaks_lightblue.svg
          filters:
            brightness: 0.7
          parallax: false
          position: center
          size: cover
      
  - block: markdown
    id: study
    content:
      title: 📚 나의 공부 방향
      subtitle: ''
      text: |-
        나는 자연어 처리 및 정보 검색 분야에 많은 관심을 가지고 있다. 
        


        현재는 BERT 등을 활용해 여러 문장을 비교하는 Task를 중심으로 이를 응용해 상품 검색에서 응용할 수 있는 방향도 살펴보고 있다.  
        현재는 Sparse Retrieval, Dense Retrieval에 활용하는 여러 모델들을 응용 및 활용해보려 하고 있다.
    design:
      columns: '1'

  - block: slider
    content:
      title: My Goal
      slides:
      - title: 개발자
        content: 작은 코드로 큰 변화를 만들며, 기술로 세상을 혁신하는 개발자가 되겠습니다.
        align: justify
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
      - title: 자연어 처리
        content: 사람과 기계 사이의 언어의 경계를 허물어, 기계와의 소통을 자연스럽게 이어주는 NLP 전문가를 꿈꿉니다.
        align: justify
        background:
          image:
            filename: NLP.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#555'
      - title: 정보 검색
        content: 
          방대한 데이터 속에서 가치를 찾아내는, 스마트한 정보 탐색의 선두주자가 되겠습니다.
        align: justify
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
      - title: 언어 모델
        content: 
          인간의 언어적 사고를 재현하는 언어 모델 개발에 기여하고 싶습니다.
        align: justify
        background:
          image:
            filename: LLM.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
      - title: 기계 학습
        content: 
          끊임없는 학습을 통해 기계가 스스로 진화하도록 이끌고, 더 나은 미래를 위한 인공지능 모델을 만들고 싶습니다.
        align: justify
        background:
          image:
            filename: ML.jpg
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
    id: project1
    content:
      title: School Projects 
      subtitle: ""
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
      page_type: school_projects
    design:
      view: community/custom_card_max_width_600
      columns: '1'

  - block: collection
    id: project2
    content:
      title: Other Projects
      subtitle: ""
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
      page_type: other_projects
    design:
      view: community/custom_card_max_width_600
      columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: collection
    id: print
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        # publication_type: 'article'
    design:
      view: community/custom_citation_card
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
