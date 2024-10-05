---
title: TREC2024 Product Search Track
subtitle: TREC2024 Product Search Track
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



Sparse Retrieval과 Dense Retrieval을 동시에 진행하는 Two-tower model로 실험을 진행했다.



**특징**



상품 문서 요약을 통해 상품 데이터 간의 연관성을 강화했으며, 훈련된 언어 모델을 통해 Two-Tower 모델 실험을 진행했다. Sparse Retrieval의 경우 Token Activation을 위한 function으로 기존의 ReLU 방식 대신 GeLU를 사용해 성능을 끌어올려보고자 하고 있다.