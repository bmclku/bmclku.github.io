---
title: "Task-specific feature extraction and classification of fMRI volumes using a deep neural network initialized with a deep belief network: Evaluation using sensorimotor tasks"
authors:
- hojinjang
- Plis M. Sergey
- Calhoun D. Vince
- Jong-Hwan Lee
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2017-01-15T00:00:00Z"
doi: ""

# # Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
# publication: "*Journal of Source Themes, 1*(1)"
publication: "*Neuroimage, 145*, 314-328"
publication_short: ""

abstract: Feedforward deep neural networks (DNN), artificial neural networks with multiple hidden layers, have recently demonstrated a record-breaking performance in multiple areas of applications in computer vision and speech processing. Following the success, DNNs have been applied to neuroimaging modalities including functional/structural magnetic resonance imaging (MRI) and positron-emission tomography data. However, no study has explicitly applied DNNs to 3D wholebrain fMRI volumes and thereby extracted hidden volumetric representations of fMRI that are discriminative for a task performed as the fMRI volume was acquired. Our study applied fully connected feedforward DNN to fMRI volumes collected in four sensorimotor tasks (i.e., left-hand clenching, right-hand clenching, auditory attention, and visual stimulus) undertaken by 12 healthy participants. Using a leave-one-subject-out cross-validation scheme, a restricted Boltzmann machinebased deep belief network was pretrained and used to initialize weights of the DNN. The pretrained DNN was fine-tuned while systematically controlling weight-sparsity levels across hidden layers. Optimal weight-sparsity levels were determined from a minimum validation error rate of fMRI volume classification. Minimum error rates (mean ± standard deviation; %) of 6.9 (± 3.8) were obtained from the three-layer DNN with the sparsest condition of weights across the three hidden layers. These error rates were even lower than the error rates from the single-layer network (9.4 ± 4.6) and the two-layer network (7.4 ± 4.1). The estimated DNN weights showed spatial patterns that are remarkably task-specific, particularly in the higher layers. The output values of the third hidden layer represented distinct patterns/codes of the 3D whole-brain fMRI volume and encoded the information of the tasks as evaluated from representational similarity analysis. Our reported findings show the ability of the DNN to classify a single fMRI volume based on the extraction of hidden representations of fMRI volumes associated with tasks across multiple hidden layers. Our study may be beneficial to the automatic classification/diagnosis of neuropsychiatric and neurological diseases and prediction of disease severity and recovery in (pre-) clinical settings using fMRI volumes without requiring an estimation of activation patterns or ad hoc statistical evaluation.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
# featured: false

links:
- name: "Link"
  url: https://www.sciencedirect.com/science/article/abs/pii/S1053811916300362
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
