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
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: experience
    content:
      text: "111"
    design:
      view: community/card2
      columns: 1
  - block: markdown
    id: future_goal
    content:
      title: future goal
      text: ''
    design:
      # Choose a layout view
      view: community/card1
      spacing:
        padding: [0, 0, 0, 0]
---
