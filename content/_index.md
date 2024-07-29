---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: ''
    design:
      columns: '1'
      background:
        image: 
          filename: front_banner.png
          parallax: false
          size: cover
      css_class: "frontbanner-top"

  - block: markdown
    content:
      title: <font size=6>Welcome to the Human-Machine Cognition Lab!</font>
      text: 고려대학교 인간-기계 인지 연구실 사이트 방문을 환영합니다👋
    design:
      background:
        color: white
      spacing:
        padding: ["2em", 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "frontbanner-bottom"

  - block: markdown
    content:
      # title: About
      text: |
        Our team aims to uncover the computational dynamics that differentiate high-level cognition in humans and machines. We explore the computational principles and neural mechanisms in the brain that enable effortless interaction with our environment and leverage these insights to advance machine models. As machines become integral to daily life, the demand for trustworthy, human-compatible models cannot be overstated. We envision a future where humans and machines work together seamlessly, with technology augmenting human tasks. If our vision aligns with your goals, please contact([✉️](contact)) the PI to discuss collaboration or joining our team.

        고려대학교 인간-기계 인지 연구실은 인간과 기계의 고차원 인지 과정의 차이를 심층적으로 연구합니다. 최근 딥러닝의 발전으로 인한 기계의 인지 능력 향상은 표면적으로 인간의 인지 과정과 유사해 보이나, 본질적인 차이가 존재합니다. 본 연구실은 Psychophysics, fMRI, EEG 등을 활용한 심리학 및 뇌공학의 다학제적 접근법을 통해 인간의 인지 행동과 신경학적 메커니즘을 연구하고 있습니다. 이를 기반으로 다양한 인공지능 모델과의 비교 분석을 수행하여 인간 중심의 신뢰성 높은 모델을 개발하는 것을 목표로 합니다. 주요 연구 주제는 <b>시지각</b>, <b>인간-기계 인지</b>, <b>뇌 기반 인공지능</b>, <b>브레인 디코딩</b>입니다. 인문학적 통찰력과 공학적 전문성을 결합하고자 하는 대학원생 및 학부 연구생 모두 환영합니다. 연구 경험이나 연구실 참여에 관심이 있으신 분은 연구 책임자에게 이메일([✉️](contact))로 문의해 주시기 바랍니다. 
    design:
      columns: '1'
      background:
        color: "#FFFFFF"
      spacing:
        padding: ["2em", "0em", "2em", "0em"]
        margin: [0, 0, 0, 0]
      css_class: "frontblock"

  - block: markdown
    content:
      title: Research Interests
      text: |
        Our current research interests include (but are not limited to) the following topics:
        <ul>
          <li><b>Visual Perception:</b> Robust visual perception, Object and face recognition, Visual attention</li>
          <li><b>Human-Machine Cognition:</b> Illusions, High-level reasoning, Contextual and semantic understanding</li>
          <li><b>Brain-Inspired AI:</b> Recurrent processing, Predictive coding, Developmental learning</li>
          <li><b>Brain Decoding</b></li>
        </ul>
        For more details, please refer to the Research page(<a href={{< ref "research" >}}>✍️</a>).    
    design:
      columns: '1'
      background:
        color: "#FFFFFF"
      spacing:
        padding: ["2em", "0em", "2em", "0em"]
        margin: [0, 0, 0, 0]
      css_class: "frontblock"

  
  - block: markdown
    content:
      title: Latest News
      text: |
        <div><b>2024.03</b></div>
        <ul>
          <li>Our paper "Improved modeling of human vision by incorporating robustness to blur in convolutional neural networks" has been published in <i>Nature Communications</i>!</li>
          <li>Hojin Jang has been appointed to the position of Assistant Professor in the Department of Brain and Cognitive Engineering at Korea University and the Human-Machine Cognition Lab's website has launched.</li>
        </ul>
    design:
      columns: '1'
      background:
        color: '#FFFFFF'
        # color: '#f6f9fb'
      spacing:
        padding: ["2em", "0em", "2em", "0em"]
      css_class: "frontblock"
        
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
      background:
        color: white
      spacing:
        padding: [0, 0, 0, 0]

---