---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  

  - block: slider
    content:
      slides:

      - title: My advantages
        content: These are my advantages
        align: center
        background: 
          image:
            filename: advantage.jpg
            filters:
              brightness: 0.4
          position: center

      - title: Linux Development
        content: Developing S/W that connects front and back in real time
        align: center
        background:
            image:
              filename: linux_slide.jpg
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
              filename: mobile_slide.jpg
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
              filename: web_slide.jpg
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



  - block: collection
    id: experience
    content:  
      title: My CS Experience
      text: This is my cs experience.
      order: desc
      filters:
        folders:
          - experience1-1
          - experience1-2
          - experience2-1
          - experience2-2
          - experience3-1
    desgin:
      view: community/card2
      columns: '2'


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
      view: article-grid
      columns: 1
---
