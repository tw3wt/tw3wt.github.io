---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: people
    content:
      title: My PortFolio
      subtitle: 사진 혹은 이름을 클릭하면 프로필로 이동합니다.
      # Choose a user profile to display (a folder name within `content/authors/`)
      user_groups:
        - admin
      text: 
    design:
      show_interests: false
      show_role: true
      show_social: true
      css_class: dark
      background:
        color: white
        image:
          # Add your image background to `assets/media/`.
          filename: background.png
          filters:
            brightness: 0.7
          size: cover
          position: center
          parallax: false
        overlay:  # 오버레이 추가
          color: '#ffffff'  # 흰색
          opacity: 0.7 

  

  - block: slider
    content:
      slides:

      - title: My advantages
        content: These are my advantages
        align: center
        background: 
          image:
            filename: advantage.png
            filters:
              brightness: 0.4
          position: center

      - title: Linux Development
        content: Developing S/W that connects front and back in real time
        align: center
        background:
            image:
              filename: linux_slide.png
              filters:
                brightness: 1
            overlay:
              color: '#0000ff'
              opacity: 0.5
            position: center
            color: '#0000ff'

      - title: Mobile & DB
        content: Developing mobile app with database
        align: center
        background:
            image:
              filename: mobile_slide.png
              filters:
                brightness: 1
            overlay:
              color: '#0000ff'
              opacity: 0.5
            position: center
            color: '#0000ff'

      - title: Web dev
        content: Front-side web development
        align: center
        background:
            image:
              filename: web_slide.png
              filters:
                brightness: 1
            overlay:
              color: '#0000ff'
              opacity: 0.5
            position: center
            color: '#0000ff'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000



  - block: features
    id: experience
    content: 
      title: My CS Experience
      text:
      items:
        - name: C
          description: 
        - name: C++
          description: 
        - name: CS Introduction
          description:
        - name: Data Structure
          description:  
        - name: Linear Algebra
          description: 
        - name: Linux
          description: 
        - name: Logic Design
          description: 
        - name: OOP
          description: 
        - name: Algorithm
          description: 
        - name: Computer Architecture
          description:
        - name: Data Communication
          description: 
        - name: Discrete Mathematics
          description: 
        - name: Mobile
          description:
        - name: Probablity & Statistics
          description:  
        - name: Artificial Intelligence
          description: 
        - name: Database
          description: 
        - name: Network
          description:
        - name: Numerical Analysis
          description: 
        - name: OS
          description:  
        - name: PL
          description: 
    desgin:
      view: community/card1
      columns: '3'


  - block: features
    id: future_goal
    content:
      title: Future Goal
      items:
        - name: "Goal 1"
          description: "Become a game developer."
        - name: "Goal 2"
          description: "Master AI technologies."
        - name: "Goal 3"
          description: "Build my own game."
    design:
      # Choose a layout view
      view: article-grid
      columns: 1
  
  - block: collection
    id: projects
    content:
      title: My Projects
      text: I enjoy making things. Here are a selection of projects that I have worked on over the years.
      filters:
        folders:
          - project
    design:
      view: community/card2
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="contact/" cta_text="Contact" %}}
    design:
      columns: '1'
---
