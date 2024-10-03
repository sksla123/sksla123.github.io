---
# Display name
title: 박준용

# Name pronunciation (optional)
name_pronunciation: Park Jun Yong

# Full name (for SEO)
first_name: 준 용
last_name: 박

# Status emoji
status:
  icon: 🤔

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: 학부 연구생

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: 전북대 정보마이닝 연구실
    url: http://imine.jbnu.ac.kr/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:pjy010608@naver.com'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/sksla123

interests:
  - Artificial Intelligence (AI)
  - Natural Language Processing (NLP)
  - Information Retrieval (IR)

education:
  - area: It정보공학과
    institution: 전북대학교 전주캠퍼스
    date_start: 2020-03-01
    date_end: ''
    summary: |
      이 곳에서 여러 개발 언어를 배우고, 심화 기술(자료구조, 알고리즘, 인공지능)을 습득했다.
      여러 좋은 교수님들과 동기들을 만나 여러가지 기회를 잡을 수 있었다.
work:
  - position: 학부연구생
    company_name: 전북대학교 정보마이닝연구실
    company_url: 'http://imine.jbnu.ac.kr'
    company_logo: ''
    date_start: 2023-04-01
    date_end: ''
    summary: |
      정보마이닝 연구실 소속으로 딥러닝과 AI에 기반한 차세대 정보검색 기술을 연구했다.

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: 기술
    items:
      - name: 파이썬
        description: ''
        percent: 100
        icon: code-bracket
      - name: 데이터 과학
        description: ''
        percent: 80
        icon: chart-bar
      - name: SQL
        description: ''
        percent: 80
        icon: circle-stack
  - name: 취미
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: 책 읽기
        description: |2-
          과학 분야의 책을 좋아하며, 최근엔 인간의 정신과 심리학과 관련된 책을 보고 있다.
          수 많은 별들과 이 우주에 함께 살아가는 우리에 대한 이야기를 담은 칼 세이건의 코스모스라는 책을 좋아한다.
        percent: 90
        icon: book-open

languages:
  - name: 한국어
    percent: 100
  - name: 영어
    percent: 60

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: 2023년 한국디지털콘텐츠학회 추계종합학술대회 대학생 논문경진대회 은상
    url: '/uploads/2023DCS_student.pdf'
    date: '2023-11-10'
    awarder: 한국디지털콘텐츠학회
    icon: DCS_icon
    summary: |
      BM25 기반의 엘라스틱 서치와 DeBERTa를 Two-Stage로 활용해 검색 성능을 더욱 끌어올리는 방안을 제시하였다. 기존의 질의 및 상품 문서 데이터를 분석하여 필요한 전처리 기법을 고안하였으며, Pseudo Relevance Feedback 기법을 사용해 사용자의 의도에 더욱 가깝게 검색할 수 있도록 제시했다.
  - title:  AI 전공특화 프로그램 발표회 우수상
    url: 'https://csai.jbnu.ac.kr/csai/29107/subview.do?enc=Zm5jdDF8QEB8JTJGYmJzJTJGY3NhaSUyRjQ5MjklMkYzMTU2MTklMkZhcnRjbFZpZXcuZG8lM0ZwYWdlJTNEMSUyNnNyY2hDb2x1bW4lM0RzaiUyNnNyY2hXcmQlM0RhaSUyNmJic0NsU2VxJTNEJTI2YmJzT3BlbldyZFNlcSUzRCUyNnJnc0JnbmRlU3RyJTNEJTI2cmdzRW5kZGVTdHIlM0QlMjZpc1ZpZXdNaW5lJTNEZmFsc2UlMjZwYXNzd29yZCUzRCUyNg%3D%3D'
    date: '2023-12-26'
    awarder: 컴퓨터인공지능학부
    icon: JBNU_Enblem
    summary: |
      다른 모델을 활용해 기존의 학습 데이터를 증강했고, 이를 기반으로 자동차 모델을 생성하는 diffusion model을 만들어내었다.
  - title: TREC2024 Product Search Track 참가
    url: 'https://www.notion.so/TREC-2024-0e456ef7f1d242b99e3d68c8fe1c51c7'
    date: '2024-08-11'
    awarder: National Institute of Standards and Technology (NIST)
    icon: TREC
    summary: |
      TREC2024 Product Search Track 부문에서는 기존의 검색 엔진 보다 더 뛰어난 효율을 낼 수 있는 새로운 모델을 찾는 것을 목표로 했다. 우리는 Sparse Retrieval과 Dense Retrieval의 결합을 통해 더 높은 성능을 낼 수 있는 방법을 찾는 것을 목표로 하여 제출하였다.
      
      <script>
          document.addEventListener('DOMContentLoaded', function() {
              function updateSvgSizes() {
                  // "Awards"라는 텍스트를 가진 요소 찾기
                  const targetElement = [...document.querySelectorAll('*')]
                      .find(el => el.textContent.trim() === 'Awards');

                  // 요소가 존재하는지 확인
                  if (targetElement) {
                      // 상위 요소에서 SVG 찾기
                      const parentElement = targetElement.parentElement; // 부모 요소 저장

                      // 부모 요소의 자식 중 div 찾기
                      const svgElements = [...parentElement.querySelectorAll('div')]
                          .flatMap(div => Array.from(div.querySelectorAll('svg')));

                      // SVG 스타일 적용
                      if (svgElements.length > 0) {
                          svgElements[0].style.width = '100px';  // 첫 번째 SVG
                      }
                      if (svgElements.length > 1) {
                          svgElements[1].style.width = '100px';  // 첫 번째 SVG
                      }
                      if (svgElements.length > 2) {
                          svgElements[2].style.width = '30px';   // 두 번째 SVG
                      }
                  }
              }

              // SVG 크기를 업데이트하는 함수 호출
              updateSvgSizes();
          });
      </script>
  
---

## About Me

현 전북대학교 IT정보공학과 재학생으로, 데이터마이닝 연구실의 학부연구생이다. 현재는 BERT, GPT 등 여러 LLM 모델에 관심을 가지고 공부하고 있으며, 자연어 처리, 정보 검색과 관련된 프로젝트를 진행해보고 있다. 
