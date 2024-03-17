---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: Welcome to the Human-Machine Vision Lab!
      text: 고려대학교 인간-기계 비전 연구실 사이트 방문을 환영합니다.
    design:
      spacing:
        # padding: [10, 0, 0, 0]
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # css_class: "dark frontbanner"
      css_class: "frontbanner"
      background:
        # color: "navy"
        image:
          filename: front_banner.png
          parallax: true
          filters:
            brightness: 0.9
  
  - block: markdown
    content:
      title: About
      text: |
        Our team endeavors to uncover the intricate computational processes underlying visual cognition in both humans and machines. This pursuit involves delving into the computational principles and neural mechanisms within the brain that enable stable visual representations of our environment. In parallel, we leverage understanding from human cognition to improve machine models. In an age where machines are increasingly integrated into our daily lives and play a crucial role in society, the need for reliable, human-compatible machine models is critical. We envision a future where machines and humans work together seamlessly, with technology augmenting human tasks and activities. If our vision aligns with your academic or professional pursuits, feel free to contact the PI to discuss collaboration opportunities or to learn more about becoming a member of our team.
    design:
      columns: '1'
      background:
        color: "#FFFFFF"
      spacing:
        # padding: ["20px", 0, "20px", 0]
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]

  - block: markdown
    content:
      title: Latest News
      subtitle: " "
      text: |
        <div><b>2024. 03.</b> Our paper "Improved modeling of human vision by incorporating robustness to blur in convolutional neural networks" has been published in <i>Nature Communications</i>!</div>
        <div><b>2024. 03.</b> The Human-Machine Vision Lab's website has launched!</div>
        <div><b>2024. 03.</b> Hojin Jang has been appointed to the position of Assistant Professor in the Department of Brain and Cognitive Engineering at Korea University!</div>
    design:
      columns: '1'
      background:
        color: '#f6f9fb'

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