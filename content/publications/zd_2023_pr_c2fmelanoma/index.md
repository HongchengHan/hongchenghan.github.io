---
title: "Coarse-to-fine feature representation based on deformable partition attention for melanoma identification"
authors:
- Dong Zhang
- Jing Yang
- Shaoyi Du*
- hanhc
- Yuyan Ge
- Longfei Zhu
- Ce Li
- Meifeng Xu*
- Nanning Zheng

author_notes:
-
-
- "Corresponding author"
-
-
-
-
- "Corresponding author"
- 

date: "2023-04-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "Patern Recognition"
  volume: 136
  # issue: A
  # page: 3380 - 3393

peer_reviewed: False
open_access: False
license: CC-BY-4.0

# Awards, honors, and recognitions. Surfaced as badges on the page and in listings.
# Note: a Test of Time award years after publication uses an explicit `date` that differs from the page date.

abstract: "In the histopathological melanoma image diagnosis system, manual identification of super-scale slides with dense cells is tedious, time-consuming, and subjective. To deal with this problem, we propose an automatic identification network based on the deformable partition attention to identify lots of dense slides as an assistant. A coarse-to-fine strategy is adopted in feature representation and qualitative identification to improve the identification accuracy of melanomas and nevi. First of all, because it is difficult to extract features in the lesion area with blurred boundaries and uneven distribution, we develop a deformable partition attention module, which integrates the advantage of the attention mechanism and deformable convolution. The module overcomes the limitation of rectangular convolution and gradually refines the channel and spatial features, which enriches feature representation by combining global and local features. Secondly, to address the problem of difficult convergence and poor recognition rate caused by the excessive non-aligned distance between benign-malignant and benign subcategories, we propose a progressive architecture via a coarse sub-network closely followed by a fine sub-network. Moreover, to further increase the inter-class differences and reduce the intra-class disparities, we propose a joint loss function to mine hard samples, which effectively improves the identification performance. Experimental results on the clinical dataset show that the proposed algorithm has higher sensitivity and specificity and outperforms state-of-the-art deep neural networks."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Patern Recognition
featured: False

hugoblox:
  ids:
    doi: 10.1016/j.patcog.2022.109247

links:
  - type: source
    url: https://www.sciencedirect.com/science/article/abs/pii/S0031320322007269
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
