---
title: Wiki
date: 2024-12-31

type: landing

sections:
  - block: markdown
    content:
      title: Wiki
      text: |
        고려대학교 뇌기계인지 연구실은 심리학, 뇌공학, 인공지능 등 다양한 학문적 접근을 통해 인간과 기계의 고차원 인지 과정을 심층적으로 연구하는 것을 목표로 합니다. 대학원생은 심리학적 통찰력과 공학적 전문성을 결합하여 융합 소양을 갖추고, 다학제적 연구자로 성장하는 것을 지향합니다. 이상적인 학습 및 연구 로드맵은 다음과 같습니다.

        ![Roadmap](timetable.png " ")

        ### 기본 트레이닝 (Basic Training)
        연구실 활동의 초기 단계에서는 연구를 위한 기초 머신러닝 능력을 습득하고 관심 있는 연구 분야를 탐구하는 것을 목표로 합니다. 이를 위해 학부연구생 및 대학원생들은 기본적인 학습 자료를 바탕으로 연구에 필요한 이론적 토대를 다지고, 최신 논문을 검토하며 관심 있는 주제를 구체화합니다.

        > Raschka, S., Liu, Y. H., & Mirjalili, V. (2022). Machine learning with PyTorch and Scikit-learn. Packt Publishing.

        > Gazzaniga, M. S., Ivry, R. B., & Mangun, G. R. (2018). Cognitive neuroscience: The biology of the mind. W.W. Norton & Company.

        위 교과서를 통해 머신러닝의 기초 개념을 확립하고, 인지 신경과학 교재에서는 개인적으로 흥미로운 주제를 선정해 인지 분야에 대한 기본적인 지식을 습득합니다. 만약 주제를 선택하는 데 어려움이 있다면, 6장 "Object Recognition"을 추천합니다. 
        
        추가로, 기본 트레이닝 기간 동안 연구생은 자신이 흥미를 느끼는 주제를 중심으로 최신 논문을 찾아 검토합니다. 다음은 논문 탐색을 위한 가이드라인입니다:
        1. Computer Science 및 Engineering 분야: NeurIPS, ICLR, ICML, CVPR, ICCV, ECCV 등 주요 컨퍼런스, 또는 Nature Machine Intelligence, Nature Computational Science, Journal of Machine Learning Research, IEEE Transactions on Pattern Analysis and Machine Intelligence 등 학술 저널지에서 발표된 최근 2년간 발표된 논문 중 3편 선정.
        2. Neuroscience 및 Psychology 분야: Nature, Nature Neuroscience, Nature Communications, Nature Human Behavior, Science, Science Advances. Cell, Neuron, Current Biology, PNAS, PLOS Biology, PLOS Computational Biology 등 학술 저널지에서 발표된 최근 4년간 발표된 논문 중 3편 선정.
        
        최종적으로 PI와의 상담을 통해 연구 방향과 부합하는 2개의 논문을 선정하고, 이를 발표하며 연구 주제를 구체화합니다.

        ### 연구 및 실습 (Research and Skills Development)
        연구 및 실습 단계에서는 연구 주제와 프로젝트/과제에 따라 필요한 기술과 소양을 학습합니다. 이 과정은 Computational, Behavioral, fMRI, EEG의 네 가지 주요 영역으로 나뉘며, 아래는 각 영역의 세부 내용입니다.

        #### Computational Skills
        인공지능 연구에 필요한 기초 수학 지식과 최신 기술 구현 능력을 습득합니다. 

        > Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep learning. MIT Press.

        위 교재(<a href="https://www.deeplearningbook.org/">링크</a>)의 Part 1과 Part 2에서 다루는 기초 수학 개념과 신경망 학습의 원리를 추천합니다.

        
        이 단계에서는 머신러닝과 딥러닝의 이론과 실습 능력을 습득하고 이를 활용하여 데이터 분석과 모델 개발을 수행합니다. 학습 자료로는 Deep Learning (Bengio, Goodfellow & Courville, 2017)과 Machine Learning with PyTorch and Scikit-Learn (Raschka et al., 2022)을 사용합니다. 연구생들은 Python 기반의 PyTorch, TensorFlow와 같은 딥러닝 프레임워크를 익히고, Pandas와 NumPy 등을 활용해 데이터 전처리와 시각화 과정을 수행합니다. 이후 실제 연구 데이터를 기반으로 모델을 설계하고 성능을 평가하며, 이를 통해 연구 주제를 구체화합니다.

        #### Behavioral Research

        Research: 융합 소양을 위하여, 개인 프로젝트 또는 과제에 맞추어 다음 툴을 익힐 수 있다.
        - Computational: Advanced: Bengio, Y., Goodfellow, I., & Courville, A. (2017). Deep learning (Vol. 1). Cambridge, MA, USA: MIT press. Parts 1 & 2. link: https://www.deeplearningbook.org/ 
        - Behavior: Morling, B. (2021). Research methods in psychology: Evaluating a world of information (5th ed.). W.W. Norton & Company. Part I, Introduction to Scientific Reasoning 읽어보길 추천. 
        - 행동실험 디자인을 위해서는, psychopy를 사용한다. Python IDE (e.g., PyCharm)과 연동된 Coder 스타일로 익숙해짐. https://psychopy.org/documentation.html 체크하웃 해보기.
        - fMRI: Poldrack, R. A., Mumford, J. A., & Nichols, T. E. (2011). Handbook of functional MRI data analysis. Cambridge University Press. link: https://www.cambridge.org/core/books/handbook-of-functional-mri-data-analysis/8EDF966C65811FCCC306F7C916228529
        - fMRI 분석툴로서는 fMRIPrep 활용. Esteban, O., Markiewicz, C. J., Blair, R. W., Moodie, C. A., Isik, A. I., Erramuzpe, A., ... & Gorgolewski, K. J. (2019). fMRIPrep: a robust preprocessing pipeline for functional MRI. Nature methods, 16(1), 111-116. 튜토리얼은 https://fmriprep.org/en/stable/.
        - EEG: Cohen, M. X. (2014). Analyzing neural time series data: Theory and practice. MIT Press. LINK: https://direct.mit.edu/books/monograph/4013/Analyzing-Neural-Time-Series-DataTheory-and
        - Handons experimce는 다음 튜토리얼 이용: https://eeglab.org/.

        - 연구실 기본 규칙:
        연구 윤리 준수: 실험 데이터 수집 및 처리 시 IRB 지침 준수. 모든 논문 및 보고서 작성 시 표절 금지.
        커뮤니케이션: 출결 관련 소통. 위클리 리포트.

        - 졸업 요건:
        석사: SCIE (SSCI 포함) 제 1 저자로 논문 1편 게재 또는 투고함.
        박사: SCIE (SSCI 포함) 제 1 저자로 논문 3편 게재하거나 최종 게재 승인 받음. 

    design:
      columns: '1'
      background:
        color: "#FFFFFF"
      spacing:
        padding: ["2em", "0em", "2em", "0em"]
        margin: [0, 0, 0, 0]
      css_class: "wiki"
      
---
