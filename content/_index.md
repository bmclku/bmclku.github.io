---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: <font size=6>Machine to Brain</font>
        content:  Understand how the brain reliably perceives and processes the complexity of the real world using machine learning approaches
        align: right
        background:
          image:
            filename: machine_to_human.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        # link:
        #   text: Image by Freepik
        #   url: https://www.freepik.com/free-photo/doctor-looking-ct-scan_25053976.htm#&position=13&from_view=search&track=ais&uuid=85ac9bf9-ff54-4a1b-acf2-e27914c0628b
      - title: <font size=6>Brain to Machine</font>
        content: Design an advanced brain-inspired model using insights from psychology and neuroscience for real-world applications
        align: left
        background:
          image:
            filename: human_to_machine.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: <font size=6>Brain and Machine</font>
        content: Pursue a future where human-machine interaction is seamless and intuitive by bridging the cognitive and functional gap between human intelligence and AI systems
        align: left
        background:
          image:
            filename: human_and_machine.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      # slide_height: 
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 5000
      css_class: "frontbanner-top"
  
  # - block: hero
  #   content:
  #     # title:
  #     # subtitle:
  #     # text: 
  #     cta_note:
  #       label: >- 
  #         <div align="right" style="font-size:12px;">Images <a href="https://www.freepik.com/free-photo/doctor-looking-ct-scan_25053976.htm#&position=13&from_view=search&track=ais&uuid=85ac9bf9-ff54-4a1b-acf2-e27914c0628b">1</a> <a href="https://www.freepik.com/free-photo/middle-eastern-cybersecurity-professional_136128971.htm#fromView=search&page=1&position=0&uuid=97f23ac3-53fb-4ed3-bdd2-625d0e6d3941">2</a> <a href="https://www.freepik.com/free-photo/young-doctor-wearing-vr-goggles-examining-mannequin-vr-simulation-future-technology-concept_9077084.htm#fromView=search&page=2&position=39&uuid=da1248e7-cc90-4989-bfbb-af3fcdd2fd9a">3</a> by Freepik</div>
  #   design:
  #     spacing:
  #       padding: [0, 0, 0, 0]
  #       margin: [0, 0, 0, 0]
  #     background:
  #       color: '#FFFFFF'

  # - block: markdown
  #   content:
  #     title: ''
  #     subtitle: ''
  #     text: ''
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: front_banner.png
  #         parallax: false
  #         size: cover
  #     css_class: "frontbanner-top"

  - block: markdown
    content:
      title: <font size=6>Welcome to the Brain and Machine Cognition Lab!</font>
      text: 고려대학교 뇌기계인지 연구실 사이트 방문을 환영합니다👋
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

        고려대학교 뇌기계인지 연구실은 심리학, 뇌공학, 인공지능 등의 다학제적 접근을 통해 인간과 기계의 고차원 인지 과정을 심층적으로 탐구합니다. 구체적으로 Psychophysics, fMRI/EEG, Computational Modeling 최신 연구 기법을 활용해 인간의 인지적 행동과 신경 메커니즘을 체계적으로 분석하며, 이를 통해 인간의 독창적인 정보 처리 방식과 사고 과정을 과학적으로 규명하는 것을 목표로 하고 있습니다. 나아가, 인간과 기계의 정보 처리 및 의사 결정 방식을 비교·분석함으로써, 인간 중심적이고 신뢰성 높은 인공지능 시스템 설계를 위한 이론적·기술적 토대를 마련하고자 합니다. 이를 위해 인문학적 통찰력과 공학적 전문성을 결합하려는 대학원생 및 학부 연구생들의 참여를 환영합니다. 연구실 참여나 협업에 관심이 있으신 분은 연구 책임자에게 이메일([✉️](contact))로 문의해 주시기 바랍니다. 
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
          <li><b>Visual Perception:</b> How does the brain integrate complex visual signals to construct a seamless perception of reality?</li>
          <li><b>Machine Cognition:</b> How can deep learning models replicate human-like contextual and semantic understanding?</li>
          <li><b>Brain-Inspired AI:</b> How can principles of brain function guide the development of more robust and capable AI systems?</li>
          <li><b>Brain Reading:</b> How can machine learning help us interpret brain activity to understand cognition?</li>
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
        - <b>[2026.03]</b> <a href="/author/yunji-cho/">Yunji Cho</a> join the lab. Welcome!
        - <b>[2025.09]</b> The paper "Category-specific perceptual learning of robust object recognition modelled using deep neural networks" has been accepted for publication in <i>PLOS Computational Biology</i>!
        - <b>[2025.09]</b> The paper "Bractive: A brain activation approach to human visual brain learning" has been accepted for publication in <i>IEEE TPAMI</i>!
        - <b>[2025.09]</b> <a href="/author/suhyun-kim/">Suhyun Kim</a>, Jiwon Kim, Juhee Suk, Minbok Lee, and Suheon Park join the lab. Welcome!
        - <b>[2025.02]</b> The paper "Configural processing as an optimized strategy for robust object recognition in neural networks" has been accepted for publication in <i>Communications Biology</i>!
        - <b>[2025.01]</b> Hojin Jang gave a talk at The International Conference on Electronics, Information, and Communication (ICEIC 2025).
        - <b>[2024.11]</b> Hojin Jang gave talks at the Korean Society of Medical and Biological Engineering and the Artificial Vision & Neural Engineering Seminar.
        - <b>[2024.03]</b> The paper "Improved modeling of human vision by incorporating robustness to blur in convolutional neural networks" has been published in <i>Nature Communications</i>!
        - <b>[2024.03]</b> Hojin Jang has been appointed to the position of Assistant Professor in the Department of Brain and Cognitive Engineering at Korea University and the Brain and Machine Cognition Lab's website has launched.
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