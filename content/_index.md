---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Wowchemy
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Wowchemy Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
  
  - block: markdown
    content:
      title: Recent News
      subtitle: " "
      text: |
        <div><b>2024. 01. 04.</b> Our paper "Improved modeling of human vision by incorporating robustness to blur in convolutional neural networks" has been accepted for publication in Nature Communications!</div>
        <div><b>2024. 01. 04.</b> Our paper "Improved modeling of human vision by incorporating robustness to blur in convolutional neural networks" has been accepted for publication in Nature Communications!</div>
    design:
      columns: '1'
      background:
        color: '#f6f9fb'

  - block: collection
    content:
      title: Research Interests
      align: center
      subtitle: " "
      text: " "
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: showcase
      columns: '1'
      background:
        color: '#FFFFFF'
  
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
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---