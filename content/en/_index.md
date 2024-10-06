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
          opacity: 1.0  


  - block: features
    id: experience
    content:
      title: My CS Experience
      text: This is my cs experience.
      image: avatar.jpg
      items:
        - name: C
          icon: code
          icon_pack: fab
        - name: CS introduction
          icon: code
          icon_pack:
        - name: C++
          icon: code
          icon_pack:
        - name: Linux
          icon: code
          icon_pack:
        - name: Logic Design
          icon: code
          icon_pack:
        - name: OOP
          icon: code
          icon_pack:
        - name: Data Structure
          icon: code
          icon_pack:
        - name: Linear Algebra
          icon: code
          icon_pack:
        - name: Probability & Statistics
          icon: code
          icon_pack:
        - name: Mobile Programming
          icon: code 
          icon_pack:
        - name: Data Communications
          icon: code
          icon_pack:
        - name: Discrete Mathematics
          icon: code
          icon_pack:
        - name: Computer Architecture
          icon: code
          icon_pack:
        - name: Algorithm
          icon: code
          icon_pack:
        - name: Numerical Analysis
          icon: code
          icon_pack:
        - name: Database
          icon: code
          icon_pack:
        - name: PL
          icon: code
          icon_pack:
        - name: Network
          icon: code
          icon_pack:
        - name: Artificial inteilligence
          icon: code
          icon_pack:
      view: community/card2
      columns: 1


  - block: markdown
    id: future_goal
    content:
      title: Future Goal
      s:
        - title: "Goal 1"
          text: "Become a game developer."
        - title: "Goal 2"
          text: "Master AI technologies."
        - title: "Goal 3"
          text: "Build my own game."
    design:
      # Choose a layout view
      view: community/card1
      columns: 1
---
