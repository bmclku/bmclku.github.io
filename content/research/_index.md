---
# title: Research Intersts

# # Listing view
# view: compact-research

# # Optional banner image (relative to `assets/media/` folder).
# banner:
#   caption: ''
#   image: interdisciplinary.jpg

title: Research Intersts
type: landing

sections:
  - block: hero
    content:
      title: Our vision is
      image:
        filename: intersect.png
      text: |
        <font size=4>To advance understanding of cognition at the intersection of cognitive psychology, neuroscience, and computer science through integrated methodologies. Our research investigates key cognitive processes, such as perception, recognition, reasoning, generalization, cognitive control, learning, memory, and social cognition, to uncover their neural and computational mechanisms and bridge the gap between biological and artificial intelligence systems.</font>
    design:
      css_class: "hero"
  
  - block: portfolio
    content:
      title: Research Interests
      subtitle: " "
      text: " "
      filters:
        folders:
          - research
        featured_only: true
        kinds:
          - page
    design:
      view: masonry
      # view: card
      # view: showcase
      # view: compact-research
      # view: article-grid
      columns: '1'
      background:
        color: '#FFFFFF'
      spacing:
        padding: ["2em", "0em", "2em", "0em"]
      css_class: "frontblock"
  
---


