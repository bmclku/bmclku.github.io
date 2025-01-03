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

        ![Roadmap](timetable.png)

        <br>

        ### 기본 트레이닝 (Basic Training)
        연구실 활동의 초기 단계에서는 연구를 위한 기초 머신러닝 능력을 습득하고 관심 있는 연구 분야를 탐구하는 것을 목표로 합니다. 이를 위해 학부연구생은 기본적인 학습 자료를 바탕으로 연구에 필요한 이론적 토대를 다지고, 최신 논문을 검토하며 관심 있는 주제를 구체화합니다. 

        > Raschka, S., Liu, Y. H., & Mirjalili, V. (2022). Machine learning with PyTorch and Scikit-learn. Packt Publishing.

        > Gazzaniga, M. S., Ivry, R. B., & Mangun, G. R. (2018). Cognitive neuroscience: The biology of the mind. W.W. Norton & Company.

        위 교과서를 통해 머신러닝의 기초 개념을 확립하고, 인지 신경과학 교재에서는 개인적으로 흥미로운 주제를 선정해 인지 분야에 대한 기본적인 지식을 습득합니다. 만약 주제를 선택하는 데 어려움이 있다면, 6장 "Object Recognition"을 추천합니다. 
        
        추가로, 기본 트레이닝 기간 동안 연구생은 자신이 흥미를 느끼는 주제를 중심으로 최신 논문을 찾아 검토합니다. 다음은 논문 탐색을 위한 가이드라인입니다:
        - Computer Science 및 Engineering 분야: NeurIPS, ICLR, ICML, CVPR, ICCV, ECCV 등 주요 컨퍼런스, 또는 Nature Machine Intelligence, Nature Computational Science, Journal of Machine Learning Research, IEEE Transactions on Pattern Analysis and Machine Intelligence 등 학술 저널지에서 발표된 최근 2년간 발표된 논문 중 3편 선정.
        - Neuroscience 및 Psychology 분야: Nature, Nature Neuroscience, Nature Communications, Nature Human Behavior, Science, Science Advances. Cell, Neuron, Current Biology, PNAS, PLOS Biology, PLOS Computational Biology 등 학술 저널지에서 발표된 최근 4년간 발표된 논문 중 3편 선정.
        
        연구생은 학습 및 논문 검토 내용을 요약한 자료(예: PPT)를 작성하여, 멘토와 협의된 일정(예: 격주 1회)에 따라 진행 상황을 점검합니다. 이를 통해 학습 방향을 지속적으로 수정 및 보완합니다. 최종적으로 PI와의 상담을 통해 연구 방향과 부합하는 2개의 논문을 선정하고, 이를 발표하며 연구 주제를 구체화합니다.

        아울러 연구생은 연구실 내 프로젝트에 참여하여 멘토를 보조하고 실제 연구 경험을 쌓습니다. 멘토는 연구생이 연구의 기초를 다지고 방향성을 설정할 수 있도록 지원하며, 필요한 기술과 이론을 습득하는 과정을 돕습니다. 이를 통해 연구실은 상호 협력과 지식 공유를 통해 모든 구성원이 함께 성장할 수 있는 환경을 지향합니다.

        <br>

        ### 연구 및 실습 (Research and Skills Development)
        연구 및 실습 단계에서는 개인 연구나 프로젝트와 관련된 주제를 세부적으로 설계하고, 이를 구현하기 위한 전문 기술과 이론적 기반을 심화합니다. 대학원생은 연구가 시작되는 학기 초에 가설 및 검증 방법론을 포함한 연구 계획을 제안하며, 매 학기 말에는 연구실 구성원들을 대상으로 연구 진행 상황과 중간 결과를 공유합니다. 이를 통해 다양한 관점에서 피드백을 받고, 연구의 방향성과 핵심 내용을 더욱 발전시킵니다. 연구 수행에 필요한 기술적 역량은 Computational, Behavioral, fMRI, EEG의 네 가지 주요 분야로 구분되며, 각 영역의 세부 내용은 다음과 같습니다.

        #### 1. Computational Skills
        인공지능 연구에 필요한 기초 수학 지식과 최신 기술 구현 능력을 습득합니다. 

        > Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep learning. MIT Press.

        위 교재(<a href="https://www.deeplearningbook.org/">링크</a>)의 Part 1과 Part 2에서 다루는 기초 수학 개념과 신경망 학습의 원리를 추천합니다.

        #### 2. Behavioral Research
        심리학적 실험 설계와 인간 행동 데이터 수집 및 분석 능력을 배양합니다.

        > Behavior: Morling, B. (2021). Research methods in psychology: Evaluating a world of information. W.W. Norton & Company.
        
        위 교재의 Part 1: Introduction to Scientific Reasoning을 통해 과학적 추론과 실험 설계의 기초 원리를 이해합니다. 이후, PsychoPy를 활용해 실험 환경을 구현하고, 연구 주제에 맞는 행동 실험 프로토콜을 개발합니다. PsychoPy의 활용법에 대한 자세한 정보는 공식 문서(<a href="https://psychopy.org/documentation.html">링크</a>)에서 확인할 수 있습니다.
        
        #### 3. fMRI Analysis
        fMRI 데이터를 전처리하고 분석하며, 뇌의 기능적 메커니즘을 이해하는 능력을 배양합니다. 
        
        > Poldrack, R. A., Mumford, J. A., & Nichols, T. E. (2011). Handbook of functional MRI data analysis. Cambridge University Press.

        위 교재(<a href="https://www.cambridge.org/core/books/handbook-of-functional-mri-data-analysis/8EDF966C65811FCCC306F7C916228529">링크</a>)를 통하여 fMRI 데이터의 처리 및 분석에 대한 전반적인 개념과 방법을 습득합니다. 이후, fMRI 데이터 전처리를 위한 도구인 fMRIPrep을 사용하여 실제 데이터를 전처리하는 방법을 익히며, 데이터 분석에 필요한 기술을 체득합니다. fMRIPrep 사용법과 관련된 자세한 정보는 관련 페이퍼(<a href="https://doi.org/10.1038/s41592-018-0235-4">링크</a>) 및 공식 문서(<a href="https://fmriprep.org/en/stable/">링크</a>)를 통해 확인할 수 있습니다.

        #### 4. EEG Analysis
        EEG 데이터를 처리하고 신경 활동의 시간적 신호를 분석하는 능력을 배양합니다.

        > Cohen, M. X. (2014). Analyzing neural time series data: Theory and practice. MIT Press.

        위 교재(<a href="https://direct.mit.edu/books/monograph/4013/Analyzing-Neural-Time-Series-DataTheory-and">링크</a>)를 활용하여 EEG 신호 분석의 이론적 배경을 학습합니다. EEG 데이터의 전처리 및 분석은 EEGLAB 소프트웨어를 사용하여 진행합니다. EEGLAB의 사용법과 관련된 구체적인 내용은 공식 문서(<a href="https://eeglab.org/">링크</a>)에서 확인할 수 있습니다.

        <br>

        ### 연구실 운영 원칙 (Lab Principles)
        우리 연구실은 책임감과 신뢰를 바탕으로, 긍정적이고 창의적인 연구 환경을 지향합니다.
        - 커뮤니케이션: 연구 진행 상황과 출결은 투명하게 소통하며, 위클리 리포트를 통해 연구 내용을 공유합니다. 멤버들 간에는 구체적이고 건설적인 피드백을 주고받되, 상호 존중과 이해를 바탕으로 부드럽고 유연한 협업 환경을 조성합니다.
        - 연구 윤리 준수: 모든 실험 데이터의 수집 및 처리는 IRB 지침에 따라 진행하며, 모든 논문과 보고서는 정직하게 작성합니다.
        - 과제 프로젝트: 연구실에서는 개인 연구 프로젝트뿐만 아니라 연구실 운영을 위한 필요한 과제 기반 프로젝트도 진행합니다.

        <br>

        ### 졸업 요건 (Graduation Requirements)
        연구실에서 석사 또는 박사 학위를 취득하기 위해서는 아래의 요건을 충족해야 합니다.
        - 석사: SCIE (또는 SSCI 포함) 저널에 제1저자로 논문 1편을 게재하거나 투고합니다.
        - 박사: SCIE (또는 SSCI 포함) 저널에 제1저자로 논문 2편을 게재하고, 추가로 1편을 게재하거나 투고합니다.  

    design:
      columns: '1'
      background:
        color: "#FFFFFF"
      spacing:
        padding: ["2em", "0em", "2em", "0em"]
        margin: [0, 0, 0, 0]
      css_class: "wiki"
      
---
