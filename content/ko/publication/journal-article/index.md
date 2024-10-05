---
title: "Search Re-ranking Through Weighted Deep Learning Model"
authors:
- Gi-Taek An
- Woo-Seok Choi
- admin
- Jung-Min Park
- Kyung-Soon Lee
author_notes:
- "First author"
- "Second author, Equal contribution"
- "Second author, Equal contribution"
- "Third author"
- "Fourth author"
date: "2024-03-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-31T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "KIPS Transactions on Software and Data Engineering"
publication_short: "TKIPS"

abstract: In information retrieval, queries come in various types, ranging from abstract queries to those containing specific keywords, making it a challenging task to accurately produce results according to user demands. Additionally, search systems must handle queries encompassing various elements such as typos, multilingualism, and codes. Reranking is performed through training suitable documents for queries using DeBERTa, a deep learning model that has shown high performance in recent research. To evaluate the effectiveness of the proposed method, experiments were conducted using the test collection of the Product Search Track at the TREC 2023 international information retrieval evaluation competition. In the comparison of NDCG performance measurements regarding the experimental results, the proposed method showed a 10.48% improvement over BM25, a basic information retrieval model, in terms of search through query error handling, provisional relevance feedback-based product title-based query expansion, and reranking according to query types, achieving a score of 0.7810.

# Summary. An optional shortened abstract.
summary: This study proposes a method for reranking search results in information retrieval using DeBERTa, addressing challenges like typos, multilingual queries, and codes. Experiments with TREC 2023 Product Search Track data show a 10.48% improvement in NDCG over BM25, with a final score of 0.7810, demonstrating the effectiveness of query error handling, query expansion, and reranking based on query types.

tags:
- Source Themes
featured: false

links:
- name: PDF
  icon: file-pdf
  icon_pack: fas
  url: https://tkips.kips.or.kr/digital-library/manuscript/file/90898/03-24M-05-010R-%EC%95%88%EA%B8%B0%ED%83%9D_221-226.pdf
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://koreascience.or.kr/article/JAKO202416957711310.page'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
