---
title: '상품 검색을 위한 딥러닝 기반 재순위화 모델'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Woo-SeokChoi
  - Gi-TaekAn
  - Kyung-SoonLee

# Author notes (optional)
author_notes:
  - 'First author, Equal contribution'
  - 'First author, Equal contribution'
  - 'Co-Author'
  - 'Corresponding author'

date: '2023-11-09T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-09T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Digital Contents Society*
publication_short: In *DCS*

abstract: 온라인 상품 검색은 질의가 추상적인 유형과 구체적인 상품을 요구하는 유형이 있어 사용자의 요구에 적합한 결과를 제시하기가 일반 정보검색에 비해 어려운 점이 있다. 또한 질의에 오타와 다국어, 상품코드를 포함하고 있어 이를 다뤄야 하는 문제를 포함하고 있다. 본 연구에서는 질의 유형을 분석하는 방법을 제안하고, 그 분석에 따라 상품 문서 결과에 대한 딥러닝 기반 재순위화 적용 여부를 판단하는 방법을 제안한다. 최근 우수한 성능을 보이는 딥러닝 모델 DeBERTa 을 이용하여 질의와 적합 문서에 대한 학습을 통해서 재순위화를 수행한다. 상품의 속성정보를 특별 정보로 처리함으로써 학습 효과를 높이도록 하였다. 국제정보검색 평가대회인 TREC2023 상품 검색 트랙에서 제공한 데이터를 활용한 평가에서 제안한 방법이 정보검색 기본 모델(BM25)에 비해 ndcg 기준 12.4% 성능이 향상됨을 확인하였다.

# Summary. An optional shortened abstract.
summary: 본 연구는 온라인 상품 검색에서 질의 유형을 분석해 딥러닝 기반 재순위화 적용 여부를 판단하는 방법을 제안한다. DeBERTa 모델과 상품 속성 정보를 활용해 성능을 향상시켰으며, TREC2023 데이터로 평가한 결과 BM25 대비 ndcg 기준 12.4% 향상을 확인했다.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

links:
- name: PDF
  icon: file-pdf
  icon_pack: fas
  url: 2023DCS_article.pdf
- name: 관련 자료 링크
  icon: newspaper
  icon_pack: fas
  url: https://docs.google.com/document/d/13qmWbdRW5u2y-hF2-uPMlJ7E5-Ellq7Y/edit?usp=drive_link&ouid=102464841454090994314&rtpof=true&sd=true

url_pdf: ''
url_code: ''
url_dataset: '' 
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
