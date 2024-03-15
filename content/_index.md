---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # - block: hero
  #   content:
  #     title: Welcome to the Human-Machine Vision Lab!
  #     image:
  #       filename: welcome.jpg
  #     text: |
  #       The **Wowchemy Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
  
  - block: markdown
    content:
      title: Welcome to the Human-Machine Vision Lab!
      subtitle: We are a group interested in both human and machine vision.
      # text: Our research interests are robustness, recurrent processing, visual perception.
    design:
      columns: '1'
      background:
        image: 
          filename: front_banner.jpg
          filters:
            GaussianBlur: 8
            brightness: 1
            opacity: 0.7
          parallax: true
          position: top
          size: contain
          text_color_light: true
      # spacing:
      #   # padding: ['20px', '0', '20px', '0']
      #   padding: [0, 0, 0, 0]
      #   margin: [0, 0, 0, 0]
      css_class: "fullscreen front_banner"

  # - block: markdown
  #   content:
  #     title: Latest News
  #     subtitle: " "
  #     text: |
  #       <div><b>2024. 03.</b> Our paper "Improved modeling of human vision by incorporating robustness to blur in convolutional neural networks" has been published in <i>Nature Communications</i>!</div>
  #       <div><b>2024. 03.</b> The Human-Machine Vision Lab's website has launched!</div>
  #       <div><b>2024. 03.</b> Hojin Jang has been appointed to the position of Assistant Professor in the Department of Brain and Cognitive Engineering at Korea University!</div>
  #   design:
  #     columns: '1'
  #     background:
  #       color: '#f6f9fb'

  # - block: features
  #   content:
  #     title: Latest News
  #     subtitle: " "
  #     text: |
  #       <div><b>2024. 03.</b> Our paper "Improved modeling of human vision by incorporating robustness to blur in convolutional neural networks" has been published in <i>Nature Communications</i>!</div>
  #       <div><b>2024. 03.</b> The Human-Machine Vision Lab's website has launched!</div>
  #       <div><b>2024. 03.</b> Hojin Jang has been appointed to the position of Assistant Professor in the Department of Brain and Cognitive Engineering at Korea University!</div>
  #     items:
  #       - name: Optimized SEO
  #         icon: magnifying-glass
  #         description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
  #   design:
  #     columns: '1'
  #     background:
  #       color: '#f6f9fb'

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
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---