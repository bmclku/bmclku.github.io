---
title: Tour
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: Machine to Human
        content: Understand how the brain maintains reliable and robust perception of the complex visual world, leveraging a range of machine and deep learning techniques
        align: right
        background:
          image:
            filename: machine_to_human.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Human to Machine
        content: Design a more advanced vision model drawing from insights in psychology and neuroscience literature to bring value to real-world applications
        align: left
        background:
          image:
            filename: human_to_machine.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Human and Machine
        content: Pursue a future where human-machine interaction is seamless and intuitive by bridging the cognitive and functional gap between human visual intelligence and machine vision capabilities
        align: left
        background:
          image:
            filename: human_and_machine.jpg
            filters:
              brightness: 0.5
            size: cover
          caption: yaho..
          position: center
          color: '#333'
        # link:
        #   icon: graduation-cap
        #   icon_pack: fas
        #   text: Join Us
        #   url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
  # - block: markdown
  #   content: 
  #     text: yaho
  #     align: right
  #     color: '#000'
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Read my latest paper on LLMs
          icon: academicons/arxiv
          url: https://arxiv.org/abs/2304.01852
        - text: Watch my new YouTube video to achieve 20x productivity
          icon: brands/youtube
          url: https://youtube.com
        - text: Connect with me on LinkedIn
          icon: brands/linkedin
          url: https://linkedin.com


    
      # link:
        # text: Image by Freepik
        # url: https://www.freepik.com/free-photo/doctor-looking-ct-scan_25053976.htm#&position=13&from_view=search&track=ais&uuid=85ac9bf9-ff54-4a1b-acf2-e27914c0628b
---
