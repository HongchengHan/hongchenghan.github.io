---
title: "Keypoint-Guided Medical Video Segmentation Model With Spatiotemporal Feature Fusion"
authors:
- Minghao Wang
- Shaoyi Du*
- Huanhuan Huo
- Juejiang
- Dong Zhang
- hanhc
- Shengdi Hou
- Juan Wang*

author_notes:
-
- "Corresponding author"
-
-
-
-
-
- "Corresponding author"

date: "2026-03-16T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-03-16T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "IEEE Transactions on Medical Imaging"
  volume: 45
  issue: 6
  # page: 3380 - 3393

peer_reviewed: False
open_access: False
license: CC-BY-4.0

# Awards, honors, and recognitions. Surfaced as badges on the page and in listings.
# Note: a Test of Time award years after publication uses an explicit `date` that differs from the page date.

abstract: "Atrial fibrillation, characterized by high prevalence and poor prognosis, presents a significant global health burden. Accurate segmentation and measurement of left ventricular and left atrial appendage morphology and function are essential for reliable risk assessment. However, these tasks are hindered by ambiguous boundaries, complex cardiac motion, and sparse annotations. To address these challenges, we propose a Keypoint-Guided Medical Video Segmentation Model with Spatiotemporal Feature Fusion (KG-STS). First, we propose a shape-constrained point encoder that explicitly encodes boundary points to improve the representation of ambiguous boundaries. Next, we introduce a motion-aware alignment module that models cardiac motion by forming coherent motion information across frames. Building on these two modules, we develop a keypoint-guided spatiotemporal feature fusion module that integrates spatial boundary representations with temporal motion cues to enhance decoding features under sparse annotations, enabling temporally consistent segmentation and supporting morphological measurement. We evaluate the segmentation and measurement performance of our method on a self-constructed multi-view transesophageal echocardiography dataset and two publicly available transthoracic echocardiography datasets. The results demonstrate that KG-STS achieves superior temporal consistency in segmentation and higher accuracy in morphological measurements compared to competing methods."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- IEEE TMI
featured: False

hugoblox:
  ids:
    doi: 10.1109/TMI.2026.3674130

links:
  - type: source
    url: https://ieeexplore.ieee.org/document/11435119
  # - type: code
  #   url: https://github.com/hongchenghan/asycmst
  # - type: dataset
  #   url: ""
  # - type: poster
  #   url: ""
  # - type: project
  #   url: ""
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: ""
  # - type: video
  #   url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  # focal_point: ""
  # preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- > [!NOTE]
> Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
