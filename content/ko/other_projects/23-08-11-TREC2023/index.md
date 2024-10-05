---
title: TREC2023 Product Search Track
subtitle: TREC2023 Product Search Track
date: 2023-06-14
image:
  focal_point: 'center'
---

TREC2023 Product Search Track 부문 참가

<!--more-->

**TREC**



TREC은 정보 검색과 관련된 Track을 주로 진행하는 세계 학술 대회 중에 하나이다.



**Product Search Track**



아마존의 상품 데이터를 기반으로 사용자가 검색한 질의에 가장 들어맞는 상품을 찾아주는 task를 주로 수행한다.



**제출물**



BM25를 기반으로 첫 단계 검색을 맞춘 후 DeBERTa를 사용해 여기서 리랭킹을 진행한다.



**특징**



성능 상승을 위해 질의 데이터 전처리를 진행했으며, Pseudo Relevance Feedback을 통해 질의 내용을 강화하여 검색하였다. 이후 학습된 모델을 불러와 리랭킹을 진행하였다.