---
title: 정 태우
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: 정 태우
      text: |-
        **Role**: 전북대학교 재학생  
        **Affiliation**: [컴퓨터 인공지능 학부](https://csai.jbnu.ac.kr/csai/index.do)  
        **Interests**: Artificial Intelligence, Computational Linguistics, Game Development  

        **Contact**: [Email](mailto:taewoo136@gmail.com)  
        **GitHub**: [tw3wt](https://github.com/tw3wt)  
        **Instagram**: [wjdtao_0612](https://www.instagram.com/wjdtao_0612/)  
        
        ## About Me
        전북대학교 컴퓨터 인공지능 학부에 재학 중인 3학년 정태우입니다. 게임 및 인공지능 분야에 관심을 가지고 있습니다.

      button:
        text: Download pdf file
        url: uploads/cloud.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          size: cover
          position: center
  
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
    id: experience
    content:
      title: card
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: future_goal
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
---
