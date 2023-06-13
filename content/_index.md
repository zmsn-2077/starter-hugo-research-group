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
        <br>

        Decisions, Interactions, and Alignment Lab at Peking University (PKU) is a energetic research team focused on advancing decision intelligence and alignment. Led by Prof.Yaodong Yang, PKU-DIAL conducts cutting-edge research to develop innovative methodologies for Reinforcement Learning, LLMs for Alignment, AI Safety.

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
