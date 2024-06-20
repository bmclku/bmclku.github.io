---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: <font size=6>Welcome to the Human-Machine Cognition Lab!</font>
      text: 고려대학교 인간-기계 인지 연구실 사이트 방문을 환영합니다👋
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
        Our team aims to uncover the computational dynamics that differentiate high-level cognition in humans and machines. We explore the computational principles and neural mechanisms in the brain that enable effortless interaction with our environment and leverage these insights to advance machine models. As machines become integral to daily life, the demand for trustworthy, human-compatible models cannot be overstated. We envision a future where humans and machines work together seamlessly, with technology augmenting human tasks. If our vision aligns with your goals, please contact([✉️](contact)) the PI to discuss collaboration opportunities or joining our team.

        고려대학교 인간-기계 인지 연구실은 인간과 기계의 고차원 인지 과정의 차이를 심층적으로 연구합니다. 심리학과 뇌공학의 융합적 접근을 통해 인지 행동 및 신경학적 원리를 탐구하며, 이를 기반으로 신뢰할 수 있는 인간 중심 인공지능 모델을 제안하는 것을 목표로 합니다. 주요 연구 주제는 <b>고차원 시각 인지</b>, <b>인간-기계 인지 메커니즘 비교</b>, <b>인간 중심 인공지능 모델</b>, <b>브레인 디코딩</b>입니다. 연구실은 인문학적 사고와 공학적 기술을 융합하고자 하는 대학원생 및 학부 연구생을 환영합니다. 협력 기회나 연구실 참여에 관심이 있으신 분은 연구 책임자에게 이메일([✉️](contact))로 문의해 주시기 바랍니다. 
    design:
      columns: '1'
      background:
        color: "#FFFFFF"
      spacing:
        # padding: ["20px", 0, "20px", 0]
        padding: ["3em", "0em", "3em", "0em"]
        margin: [0, 0, 0, 0]

  - block: collection
    content:
      title: Research Interests
      align: center
      subtitle: " "
      text: " "
      count: 4
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
      view: masonry
      # view: card
      # view: showcase
      # view: compact-research
      # view: article-grid
      columns: '1'
      # flip_alt_rows: true
      background:
        color: '#FFFFFF'
        # color: '#f6f9fb'
      spacing:
        padding: ["3em", "0em", "3em", "0em"]
  
  - block: portfolio
    id: projects
    content:
      title: Research Interests
      align: center
      subtitle: " "
      text: " "
      count: 4
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
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: markdown
    content:
      title: Latest News
      # text: |
      #   ### March 2024
      #     - Our paper "Improved modeling of human vision by incorporating robustness to blur in convolutional neural networks" has been published in <i>Nature Communications</i>!
      #     - Hojin Jang has been appointed to the position of Assistant Professor in the Department of Brain and Cognitive Engineering at Korea University and the Human-Machine Vision Lab's website has launched.
      text: |
        <div><b>2024.03</b></div>
        <ul>
          <li>Our paper "Improved modeling of human vision by incorporating robustness to blur in convolutional neural networks" has been published in <i>Nature Communications</i>!</li>
          <li>Hojin Jang has been appointed to the position of Assistant Professor in the Department of Brain and Cognitive Engineering at Korea University and the Human-Machine Vision Lab's website has launched.</li>
        </ul>
    design:
      columns: '1'
      background:
        color: '#FFFFFF'
        # color: '#f6f9fb'
      spacing:
        padding: ["3em", "0em", "3em", "0em"]
        
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