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
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
        Please reach out to collaborate 😃

        <link
          rel="stylesheet"
          href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css"
        />
        <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

        <div class="swiper swiper-material swiper-initialized swiper-horizontal swiper-watch-progress" style="--swiper-material-slide-size: 392px;">
        <div class="swiper-wrapper" style="cursor: grab;">
          <div class="swiper-slide swiper-slide-visible swiper-slide-fully-visible swiper-slide-active" style="width: 392px; margin-right: 16px; --swiper-material-scale: 1;">
            <!-- Wrap each slide content with "swiper-material-wrapper" and "swiper-material-content" elements -->
            <div class="swiper-material-wrapper" style="width: 100%; transform: translate3d(0px, 0px, 0px);">
              <div class="swiper-material-content">
                <!-- Use data-swiper-material-scale to add scale effect on required elements -->
                <img class="demo-material-image" data-swiper-material-scale="1.25" src="https://sksla123.github.io/media/stacked-peaks.svg" style="transform: scale(1);">
                <!-- Use swiper-material-animate-opacity class to add opacity animation on required elements -->
                <span class="demo-material-label swiper-material-animate-opacity" style="opacity: 1;">Slide 1</span>
              </div>
            </div>
          </div>
          <div class="swiper-slide swiper-slide-visible swiper-slide-fully-visible swiper-slide-next" style="width: 392px; margin-right: 16px; --swiper-material-scale: 0.6295918367346939;">
            <div class="swiper-material-wrapper" style="width: 62.9592%; transform: translate3d(0px, 0px, 0px);">
              <div class="swiper-material-content">
                <img class="demo-material-image" data-swiper-material-scale="1.25" src="https://sksla123.github.io/media/stacked-peaks.svg" style="transform: scale(1.0926);">
                <span class="demo-material-label swiper-material-animate-opacity" style="opacity: 1.15596e-05;">Slide 2</span>
              </div>
            </div>
          </div>
          <div class="swiper-slide" style="width: 392px; margin-right: 16px; --swiper-material-scale: 0.32959183673469383;">
            <div class="swiper-material-wrapper" style="width: 32.9592%; transform: translate3d(-145.2px, 0px, 0px);">
              <div class="swiper-material-content">
                <img class="demo-material-image" data-swiper-material-scale="1.25" src="https://sksla123.github.io/media/stacked-peaks.svg" style="transform: scale(1.1676);">
                <span class="demo-material-label swiper-material-animate-opacity" style="opacity: 0;">Slide
                  3</span>
              </div>
            </div>
          </div>
          <div class="swiper-slide" style="width: 392px; margin-right: 16px; --swiper-material-scale: 0.00001;">
            <div class="swiper-material-wrapper" style="width: 0.001%; transform: translate3d(-424px, 0px, 0px);">
              <div class="swiper-material-content">
                <img class="demo-material-image" data-swiper-material-scale="1.25" src="https://sksla123.github.io/media/stacked-peaks.svg" style="transform: scale(1.25);">
                <span class="demo-material-label swiper-material-animate-opacity" style="opacity: 0;">Slide 4</span>
              </div>
            </div>
          </div>
          <div class="swiper-slide" style="width: 392px; margin-right: 16px; --swiper-material-scale: 0.00001;">
            <div class="swiper-material-wrapper" style="width: 0.001%; transform: translate3d(-832px, 0px, 0px);">
              <div class="swiper-material-content">
                <img class="demo-material-image" data-swiper-material-scale="1.25" src="https://sksla123.github.io/media/stacked-peaks.svg" style="transform: scale(1.25);">
                <span class="demo-material-label swiper-material-animate-opacity" style="opacity: 0;">Slide 5</span>
              </div>
            </div>
          </div>
          <div class="swiper-slide" style="width: 392px; margin-right: 16px; --swiper-material-scale: 0.00001;">
            <div class="swiper-material-wrapper" style="width: 0.001%; transform: translate3d(-1240px, 0px, 0px);">
              <div class="swiper-material-content">
                <img class="demo-material-image" data-swiper-material-scale="1.25" src="https://sksla123.github.io/media/stacked-peaks.svg" style="transform: scale(1.25);">
                <span class="demo-material-label swiper-material-animate-opacity" style="opacity: 0;">Slide 6</span>
              </div>
            </div>
          </div>
          <div class="swiper-slide" style="width: 392px; margin-right: 16px; --swiper-material-scale: 0.00001;">
            <div class="swiper-material-wrapper" style="width: 0.001%; transform: translate3d(-1648px, 0px, 0px);">
              <div class="swiper-material-content">
                <img class="demo-material-image" data-swiper-material-scale="1.25" src="https://sksla123.github.io/media/stacked-peaks.svg" style="transform: scale(1.25);">
                <span class="demo-material-label swiper-material-animate-opacity" style="opacity: 0;">Slide 7</span>
              </div>
            </div>
          </div>
          <div class="swiper-slide" style="width: 392px; margin-right: 16px; --swiper-material-scale: 0.00001;">
            <div class="swiper-material-wrapper" style="width: 0.001%; transform: translate3d(-2056px, 0px, 0px);">
              <div class="swiper-material-content">
                <img class="demo-material-image" data-swiper-material-scale="1.25" src="https://sksla123.github.io/media/stacked-peaks.svg" style="transform: scale(1.25);">
                <span class="demo-material-label swiper-material-animate-opacity" style="opacity: 0;">Slide 8</span>
              </div>
            </div>
          </div>
          <div class="swiper-slide" style="width: 392px; margin-right: 16px; --swiper-material-scale: 0.00001;">
            <div class="swiper-material-wrapper" style="width: 0.001%; transform: translate3d(-2464px, 0px, 0px);">
              <div class="swiper-material-content">
                <img class="demo-material-image" data-swiper-material-scale="1.25" src="https://sksla123.github.io/media/stacked-peaks.svg" style="transform: scale(1.25);">
                <span class="demo-material-label swiper-material-animate-opacity" style="opacity: 0;">Slide 9</span>
              </div>
            </div>
          </div>
          <div class="swiper-slide" style="width: 392px; margin-right: 16px; --swiper-material-scale: 0.00001;">
            <div class="swiper-material-wrapper" style="width: 0.001%; transform: translate3d(-2872px, 0px, 0px);">
              <div class="swiper-material-content">
                <img class="demo-material-image" data-swiper-material-scale="1.25" src="https://sksla123.github.io/media/stacked-peaks.svg" style="transform: scale(1.25);">
                <span class="demo-material-label swiper-material-animate-opacity" style="opacity: 0;">Slide 10</span>
              </div>
            </div>
          </div>
        </div>
      </div>
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
