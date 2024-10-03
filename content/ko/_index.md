---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks_blue.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 나의 공부 방향'
      subtitle: ''
      text: |-
        나는 자연어 처리 및 정보 검색 분야에 많은 관심을 가지고 있다. 현재는 BERT 등을 활용해 여러 문장을 비교하는 Task를 공부하고 있고, 이를 응용해 상품 검색에서 응용할 수 있는 방향도 살펴보고 있다.
        
        현재는 Sparse Retrieval, Dense Retrieval에 활용하는 여러 모델 들을 응용 및 활용해보려 하고 있다.

        <div class="carousel-container">
          <div class="carousel">
            <div class="slides">
              <div class="slide">
                <img
                  id="slide01"
                  src="https://picsum.photos/1280/720?random=1"
                  alt="slide image"
                />
              </div>
              <div class="slide">
                <img
                  id="slide02"
                  src="https://picsum.photos/1280/720?random=2"
                  alt="slide image"
                />
              </div>
              <div class="slide">
                <img
                  id="slide03"
                  src="https://picsum.photos/1280/720?random=3"
                  alt="slide image"
                />
              </div>
              <div class="slide">
                <img
                  id="slide04"
                  src="https://picsum.photos/1280/720?random=4"
                  alt="slide image"
                />
              </div>
            </div>
            <div class="controls">
              <div class="control prev-slide">&#9668;</div>
              <div class="control next-slide">&#9658;</div>
            </div>
          </div>
        </div>

        <script>
          const delay = 3000; //ms

          const slides = document.querySelector(".slides");
          const slidesCount = slides.childElementCount;
          const maxLeft = (slidesCount - 1) * 100 * -1;

          let current = 0;

          function changeSlide(next = true) {
            if (next) {
              current += current > maxLeft ? -100 : current * -1;
            } else {
              current = current < 0 ? current + 100 : maxLeft;
            }

            slides.style.left = current + "%";
          }

          let autoChange = setInterval(changeSlide, delay);
          const restart = function () {
            clearInterval(autoChange);
            autoChange = setInterval(changeSlide, delay);
          };

          // Controls
          document.querySelector(".next-slide").addEventListener("click", function () {
            changeSlide();
            restart();
          });

          document.querySelector(".prev-slide").addEventListener("click", function () {
            changeSlide(false);
            restart();
          });

          // Hover and Click Event
          document.querySelectorAll(".slide img").forEach((slide) => {
            slide.addEventListener("mouseover", function () {
              const id = this.id;
              if (id === "slide02") {
                this.style.cursor = "pointer";
              } else {
                this.style.cursor = "default";
              }
            });

            slide.addEventListener("click", function () {
              const id = this.id;
              if (id === "slide02") {
                window.location.href = "https://www.example.com"; // 이동할 URL
              }
            });
          });
        </script>

        <style>
          * {
            margin: 0; /* 모든 요소의 기본 margin 제거 */
            padding: 0; /* 모든 요소의 기본 padding 제거 */
            box-sizing: border-box; /* 박스 모델 설정 */
          }

          .carousel-container {
            background: transparent; /* 완전한 투명으로 설정 */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 250px; /* 고정된 높이 설정 */
          }

          .carousel {
            width: 100%;
            max-width: 1280px; /* 최대 폭 설정 (원하는 대로 조정 가능) */
            height: 100%; /* 컨테이너의 높이에 맞춤 */
            border-radius: 3px;
            overflow: hidden;
            position: relative;
            box-shadow: 0 3px 6px rgba(223, 192, 192, 0.2);
          }

          .slides {
            position: absolute;
            top: 0; /* 위치를 컨테이너의 상단으로 맞춤 */
            left: 0;
            display: flex;
            width: 100%;
            height: 100%; /* 슬라이드의 높이를 컨테이너의 높이에 맞춤 */
            transition: 1s ease-in-out all;
          }

          .slide {
            min-width: 100%;
            position: relative; /* 텍스트 레이어를 위해 position 추가 */
          }

          .slide img {
            width: 100%;
            height: 100%; /* 슬라이드의 높이에 맞춤 */
            object-fit: cover; /* 이미지를 비율을 유지하며 슬라이드에 맞춤 */
          }

          .carousel:hover .controls {
            opacity: 1;
          }

          .carousel .controls {
            opacity: 0;
            display: flex;
            position: absolute;
            top: 50%;
            left: 0;
            justify-content: space-between;
            width: 100%;
            z-index: 10;
            transition: all ease 0.5s;
          }

          .carousel .control {
            margin: 0 5px;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 40px;
            width: 40px;
            border-radius: 50%;
            background-color: rgba(255, 255, 255, 0.7);
            opacity: 0.5;
            transition: ease 0.3s;
            cursor: pointer;
          }
        </style>



    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
