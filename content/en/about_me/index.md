---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: About me
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          # - Principal Investigators
          # - Researchers
          # - Grad Students
          # - Administration
          # - Visitors
          # - Alumni
          - Developer
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: false
      show_social: true
    
  - block: experience
    content:
      title: Experience
      items:
        - title: Undergraduate Researcher
          company: Data Mining Lab, Chonbuk National University
          # # 현재 정보마이닝연구실 랩 사이트를 저장하지 않았기 때문에 아래 링크로 대체
          # company_url: https://csai.jbnu.ac.kr/csai/29031/subview.do?enc=Zm5jdDF8QEB8JTJGamJudVByb2ZsJTJGY3NhaSUyRjc4NyUyRjYzNjclMkZhcnRjbFZpZXcuZG8lM0ZwYWdlJTNEMSUyNmZpbmRUeXBlJTNEJTI2ZmluZFdvcmQlM0QlMjY%3D
          company_logo: "JBNU_Emblem"
          date_start: "2023-04-06"
  
  - block: experience
    content:
      title: Education
      items:
        - title: Enrolled at Jeonbuk National University
          company: Department of IT Information Engineering, Jeonbuk National University
          company_url: https://it.jbnu.ac.kr/it/index.do
          company_logo: "JBNU_Emblem"
          date_start: "2020-03-01"

  - block: accomplishments
    content:
      title: Awards & Achievements
      items:
        - title: 2023 Fall Conference of the Digital Contents Society, Undergraduate Thesis Competition, Presentation Paper - Silver Award
          organization: Digital Contents Society
          organization_url: https://dcs.or.kr/
          date_start: "2023-05-01"
          description: "The paper was selected as the Silver Award paper in the Undergraduate Thesis Competition at the 2023 Fall Conference of the Digital Contents Society, and this award is presented in recognition of that achievement"
          certificate_url: "/uploads/award1.pdf"
---