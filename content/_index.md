---
# Leave the homepage title empty to use the site title
title:
date: 2023-06-13
type: landing

sections:
  - block: slider
    
    design:
      loop: true
      interval: 10
    content:
      slides:
      - title: PAIR Lab
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Recent News
          url: ../talks/
      # - title: Lunch & Learn ☕️
      #   content: 'Share your knowledge with the group and explore exciting new topics together!'
      #   align: left
      #   background:
      #     image:
      #       filename: contact.jpg
      #       filters:
      #         brightness: 0.7
      #     position: center
      #     color: '#555'
      - title: PKU-Alignment Team
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000
  - block: hero
    content:
      title: |
        PAIR Lab
      image:
        filename: welcome.jpg
      text: |
        At the PKU Alignment and Interaction Research Lab (PAIR Lab), we address the fundamental challenges in decision-making, strategic interactions, and value alignment within AGI. Our expertise encompasses reinforcement learning for refined decision-making, multi-agent systems and game theory for complex interactions, and RLHF techniques for secure AGI-human value alignment. Our integrative methodology aims to guide AGI development towards a safe, beneficial future in synchrony with humanity."
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
