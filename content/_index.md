---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: <font size=6>Welcome to the Human-Machine Vision Lab!</font>
      text: 고려대학교 인간-기계 비전 연구실 사이트 방문을 환영합니다👋
    design:
      spacing:
        padding: ["3em", 0, "3em", 0]
        margin: [0, 0, 0, 0]
      css_class: "frontbanner dark"
      background:
        # color: "navy"
        image:
          filename: front_banner.png
          parallax: false
          filters:
            brightness: 1
            
  - block: markdown
    content:
      # title: About
      text: |
        Our team endeavors to uncover the complex computational dynamics underlying <span style="color: #a52a2a; font-weight:bold;">visual cognition in both humans and machines</span>. This pursuit involves delving into the computational principles and neural mechanisms within the brain that enable stable visual representations of our environment. In parallel, we leverage understanding from human cognition to advance machine models. As machines become integral to our daily lives and play a crucial role in society, the demand for trustworthy, human-compatible machine models cannot be overstated. We envision a future where machines and humans work together seamlessly, with technology augmenting human tasks and activities. If our vision aligns with your academic or professional pursuits, feel free to <b>[_contact_](contact)</b> the PI to discuss collaboration opportunities or to learn more about becoming a member of our team.

        Our current research focus areas:
        - Examining the robust nature of human object and face recognition
        - Developing bio-inspired strategies for deep learning
        - Exploring the mysteries behind visual illusions
        - Understanding high-level semantic cognition 
        - Decoding human brain activity for insights into the mind
    design:
      columns: '1'
      background:
        color: "#FFFFFF"
      spacing:
        # padding: ["20px", 0, "20px", 0]
        padding: ["2em", 0, "2em", 0]
        margin: [0, 0, 0, 0]

  - block: markdown
    content:
      title: Latest News
      text: |
        ### March 2024
          - Our paper "Improved modeling of human vision by incorporating robustness to blur in convolutional neural networks" has been published in <i>Nature Communications</i>!
          - Hojin Jang has been appointed to the position of Assistant Professor in the Department of Brain and Cognitive Engineering at Korea University and the Human-Machine Vision Lab's website has launched.
    design:
      columns: '1'
      background:
        color: '#f6f9fb'
      spacing:
        padding: ["2em", 0, "2em", 0]

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
      page_type: research
    design:
      # view: showcase
      view: masonry
      columns: '1'
      background:
        color: '#FFFFFF'
      spacing:
        padding: ["2em", 0, "2em", 0]
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
      spacing:
        padding: [0, 0, 0, 0]
---