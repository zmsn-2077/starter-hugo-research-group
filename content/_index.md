---
# Leave the homepage title empty to use the site title
title:
date: 2023-06-13
type: landing

sections:
  - block: hero
    content:
      title: |
        PAIR Lab
      image:
        filename: welcome.jpg
      text: |
        At the PKU Alignment and Interaction Research Lab (PAIR Lab), we address the fundamental challenges in decision-making, strategic interactions, and value alignment within AGI. Our expertise encompasses reinforcement learning for refined decision-making, multi-agent systems and game theory for complex interactions, and RLHF techniques for secure AGI-human value alignment. Our integrative methodology aims to guide AGI development towards a safe, beneficial future in synchrony with humanity."

  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image:
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
