---
# title: Research Intersts

# # Listing view
# view: compact-research

# # Optional banner image (relative to `assets/media/` folder).
# banner:
#   caption: ''
#   image: intersect.jpg

title: Research Intersts
type: landing

sections:
  - block: hero
    content:
      title: <font size=6>Our goal is</font>
      image:
        filename: intersect.png
      text: |
        <font size=4>To explore cognition at the intersection of cognitive psychology, neuroscience, and computer science through a multidisciplinary approach. Areas of interest include perception, recognition, reasoning, cognitive control, learning, memory, and social cognition, with the goal of uncovering their neural and computational mechanisms and bridging the gap between biological and artificial intelligence systems.</font>
    design:
      css_class: "hero"
  
  - block: portfolio
    content:
      title: <div style="text-align:left;"><font size="6">Our research interests are</font></div>
      subtitle: " "
      text: " "
      filters:
        folders:
          - research
        featured_only: true
        kinds:
          - page
    design:
      # view: masonry
      # view: card
      view: showcase
      # view: compact-research
      # view: article-grid
      columns: '1'
      background:
        color: '#FFFFFF'
      spacing:
        padding: ["0em", "0em", "0em", "0em"]
      css_class: "frontblock"
  
---


