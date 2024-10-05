---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: markdown
    content:
      title: | 
        <span style='font-size:150%; font-weight:bold; color: black;'>About Me</span>
      text: | 
        <div style="display: flex; align-items: center; justify-content: space-between;">
          <div>
            <h1>👋 Hey, I'm Shiung</h1>
            <p>전북대학교 컴퓨터 인공지능 학부에 재학중인 3학년 정태우입니다. 게임 및 인공지능 분야에 관심을 가지고 있습니다. 관심분야와 마찬가지로 게임 개발, 인공지능 관련 진로를 희망하고 있습니다. 개발 관련 프로젝트 경험으로는 리눅스 프로그래밍, 모바일 프로그래밍, 데이터베이스 수업을 통한 팀 프로젝트를 진행했습니다. </p>
            <p>My interests : </p>
            <ul>
              <li>Artificial Intelligence</li>
              <li>Game Development</li>
            </ul>
            <p>Contact: ksl@jbnu.ac.kr</p>
            <div>
              <img src="path-to-image.jpg" alt="Profile Image" style="border-radius: 10px; width: 150px;">
            </div>
        </div>        
      button:
        text: Download pdf file
        url: uploads/cloud.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  
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
