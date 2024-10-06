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
      title: 📚 My study direction
      subtitle: ''
      text: |-
        I am very interested in the field of natural language processing and information retrieval.
        


        Currently, I am focused on tasks that compare multiple sentences using models like BERT, and I am also exploring how to apply this to product search. I am looking into applying and utilizing various models for Sparse Retrieval and Dense Retrieval.
    design:
      columns: '1'

  - block: slider
    content:
      title: My Goal
      slides:
      - title: Developer
        content: I aim to become a developer who makes big changes with small code and innovates the world through technology.
        align: justify
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
      - title: Natural Language Process
        content: I dream of becoming an NLP expert who breaks down the language barrier between humans and machines, facilitating natural communication with machines.
        align: justify
        background:
          image:
            filename: NLP.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#555'
      - title: Information Retrieval
        content: I aim to be a leader in smart information retrieval, uncovering value within vast amounts of data.
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
      - title: Language Model
        content: I want to contribute to the development of language models that replicate human linguistic thinking.
        align: justify
        background:
          image:
            filename: LLM.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
      - title: Machine Learning
        content: Through continuous learning, I want to guide machines to evolve on their own and create AI models for a better future.
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
