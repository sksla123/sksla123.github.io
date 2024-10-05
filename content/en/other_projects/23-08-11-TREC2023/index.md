---
title: TREC2023 Product Search Track
subtitle: TREC2023 Product Search Track
date: 2023-06-14
image:
  focal_point: 'center'
---

Participation in the TREC 2023 Product Search Track

<!--more-->

**TREC**



TREC is one of the leading international conferences focused on various tracks related to information retrieval.



**Product Search Track**



It primarily focuses on tasks that find the most relevant products based on user queries using Amazon's product data.



**Submissions**



After conducting the initial search based on BM25, we use DeBERTa for re-ranking the results.



**Features**



To improve performance, we performed query data preprocessing and enhanced the query content using Pseudo Relevance Feedback for retrieval. After that, we loaded the trained model for re-ranking.