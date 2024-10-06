---
title: 'Deep Learning-Based Re-Ranking Model for Product Search'

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

abstract: Online product search has the challenge of presenting results that meet user demands, as queries can be either abstract or specific to particular products, making it more difficult compared to general information retrieval. Additionally, queries may contain typos, multiple languages, and product codes, which need to be addressed. This study proposes a method for analyzing query types and determining whether to apply deep learning-based re-ranking to product document results based on that analysis. Re-ranking is performed using the recent deep learning model DeBERTa, which has shown excellent performance, by training on queries and relevant documents. The attribute information of products is treated as special information to enhance the learning effectiveness. An evaluation using data provided by the TREC 2023 Product Search Track, an international information retrieval evaluation competition, confirms that the proposed method improves performance by 12.4% in NDCG compared to the baseline information retrieval model (BM25).

# Summary. An optional shortened abstract.
summary: This study proposes a method for analyzing query types in online product search to determine whether to apply deep learning-based re-ranking. By utilizing the DeBERTa model and product attribute information, we enhanced performance, and the evaluation results using TREC 2023 data confirmed a 12.4% improvement in NDCG compared to BM25.

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
- name: related link
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
