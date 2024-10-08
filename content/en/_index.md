---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download pdf file
        url: uploads/cloud.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 0.7
          size: cover
          position: center
          parallax: false
        overlay:  # 오버레이 추가
          color: '#ffffff'  # 흰색
          opacity: 0.7 


  - block: collection
    content:
      id: experience
      title: My CS Experience
      text: This is my cs experience.
      count: 3
      filters:
        folders:
          - experience1-1
    desgin:
      view: views/community/card2
      columns: '5'


  - block: features
    id: future_goal
    content:
      title: Future Goal
      items:
        - name: "Goal 1"
          text: "Become a game developer."
        - name: "Goal 2"
          text: "Master AI technologies."
        - name: "Goal 3"
          text: "Build my own game."
    design:
      # Choose a layout view
      view: views/card1
      columns: 1
---
