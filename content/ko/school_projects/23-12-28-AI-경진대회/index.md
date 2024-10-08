---
title: CLIP을 이용한 확산 생성 모델 샘플링
subtitle: 2023 인공지능(AI)프로젝트 발표회
date: 2023-12-28
image:
  focal_point: 'center'
---

diffusion model을 학습시키고 이를 이용해 텍스트로 부터 이미지를 생성해내는 프로젝트를 진행해보았다. 

<!--more-->

**Diffusion Model을 활용한 이미지 생성 프로젝트**

최근에 Diffusion Model을 학습시키고, 이를 이용해 텍스트로부터 이미지를 생성해내는 프로젝트를 진행해보았습니다. Diffusion Model은 기존 데이터에 노이즈를 조금씩 더해가면서 완전한 노이즈가 될 때까지의 과정을 학습해요. 이 과정을 forward process라고 부르며, 이 과정 덕분에 모델은 𝑥_𝑡−1과 𝑥_𝑡 사이의 𝑞 값을 학습하게 됩니다.



이제 샘플링 과정에서는 학습된 𝑞값을 사용해 𝑝값을 유추하는 reverse process를 통해 이미지를 생성하게 되죠. 그런데 여기서 생성되는 이미지는 랜덤한 이미지이기 때문에 사용자가 원하는 이미지를 만들기 위해서는 추가적인 기법이 필요합니다. 이처럼 Diffusion Sampling은 모델을 활용한 샘플링을 뜻해요.



**사용자가 원하는 이미지를 생성하는 방법**

Diffusion Model에서 사용자가 원하는 사진을 만들어내는 주된 방법은 guidance를 활용하는 것이에요. 이 방식은 reverse process 과정에서 𝑦라고 하는 사용자가 원하는 이미지에 대한 정보를 추가로 부여함으로써 모델이 생성하는 이미지가 사용자가 원하는 형태에 가깝게 되도록 돕습니다.




제 프로젝트에서는 CLIP을 Diffusion 모델의 classifier로 사용했고, 𝑦로 각 클래스에 대한 임베딩 값을 샘플링했습니다. 예를 들어 “white and red car”라는 값을 𝑦로 줬을 때의 샘플링 결과를 살펴보니, “white and red car”에 대한 정보가 제대로 담겨져 있지 않음을 확인할 수 있었어요. 왜 그런 결과가 나왔을까요? 원인을 아래의 세 가지로 분석했습니다:




CLIP/Diffusion Model의 잘못된 학습


데이터 셋의 특성상 구도에 따라 차 색깔이 고정됨


Diffusion 모델과 CLIP의 이미지 크기가 다름




이렇게 프로젝트를 진행하며 여러 가지를 배우고, 또 실험을 통해 문제를 해결해 나가는 과정이 정말 흥미로웠습니다. 앞으로도 더 발전시킬 수 있도록 노력하려합니다.
