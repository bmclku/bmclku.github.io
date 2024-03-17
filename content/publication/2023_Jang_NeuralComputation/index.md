---
title: "Robustness to Transformations Across Categories: Is Robustness Driven by Invariant Neural Representations?"
authors:
- hojinjang
- Syed Suleman Abbas Zaidi
- Xavier Boix
- Neeraj Prasad
- Sharon Gilad-Gutnick
- Shlomit Ben-Ami
- Pawan Sinha
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2023-11-07T00:00:00Z"
doi: ""

# # Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
# publication: "*Journal of Source Themes, 1*(1)"
publication: "*Neural Computation, 35*(12), 1910-1937"
publication_short: ""

abstract: Deep convolutional neural networks (DCNNs) have demonstrated impressive robustness to recognize objects under transformations (e.g., blur or noise) when these transformations are included in the training set. A hypothesis to explain such robustness is that DCNNs develop invariant neural representations that remain unaltered when the image is transformed. However, to what extent this hypothesis holds true is an outstanding question, as robustness to transformations could be achieved with properties different from invariance; for example, parts of the network could be specialized to recognize either transformed or nontransformed images. This article investigates the conditions under which invariant neural representations emerge by leveraging that they facilitate robustness to transformations beyond the training distribution. Concretely, we analyze a training paradigm in which only some object categories are seen transformed during training and evaluate whether the DCNN is robust to transformations across categories not seen transformed. Our results with state-of-the-art DCNNs indicate that invariant neural representations do not always drive robustness to transformations, as networks show robustness for categories seen transformed during training even in the absence of invariant neural representations. Invariance emerges only as the number of transformed categories in the training set is increased. This phenomenon is much more prominent with local transformations such as blurring and high-pass filtering than geometric transformations such as rotation and thinning, which entail changes in the spatial arrangement of the object. Our results contribute to a better understanding of invariant neural representations in deep learning and the conditions under which it spontaneously emerges.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
# featured: false

links:
- name: "Link"
  url: https://doi.org/10.1162/neco_a_01621
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
