---
title: "基于皮肤镜图像分类的多模态医学语料库构建"
authors:
- "韩泓丞"
- "林玉萍*"
- "郭钦钵"
- "张栋"
- "许美凤"
- "朱龙飞"
- "李小棉"
- "冯丽丽"
- "岳捷*"

author_notes:
-
- "Corresponding author"
-
-
-
-
-
- 
- "Corresponding author"

date: "2023-06-25T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-06-25T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "西北大学学报(自然科学版)"
  volume: 53
  issue: 3
  # page: 377 - 386
peer_reviewed: False
open_access: False
license: CC-BY-4.0

# Awards, honors, and recognitions. Surfaced as badges on the page and in listings.
# Note: a Test of Time award years after publication uses an explicit `date` that differs from the page date.

abstract: "多模态医学语料库是医学研究、临床诊断和教学的重要工具之一。然而，现有的医学语料库大多仅有文本数据，缺乏匹配的直观图像，信息不够充分。而大量医学图像缺少明确的语义标签，导致构建语料库困难。针对上述问题，该文提出一种面向多模态医学语料库的皮肤镜图像分类方法，通过对皮肤镜图像进行精确分类获取语义标签，并结合自然语言处理方法匹配相关文本信息，从而建立图像与文本相结合的多模态语料库。首先，针对传统机器学习图像分类方法对病灶特征提取较弱且易受背景噪声影响，导致病灶分类精度差的问题，该文构建双流网络，通过融合病灶的形状与纹理特征增强病灶特征提取能力。其次，为减少特征融合导致的信息冗余，引入了基于通道注意力机制的特征筛选方法，关注关键特征并抑制噪声影响。此外，针对皮肤镜图像良恶性样本数量不均衡导致的模型优化困难问题，引入非对称损失函数，提升模型对样本不均衡的鲁棒性。在ISIC皮肤镜图像数据集上的实验结果表明，该文所提方法能够快速准确地分类皮肤镜图像，并将图像与病历文本进行精准匹配以构建多模态医学语料库。"

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- "西北大学学报(自然科学版)"
featured: False

hugoblox:
  ids:
    doi: 10.16152/j.cnki.xdxbzr.2023-03-007

links:
  - type: source
    url: https://xdxbzk.nwu.edu.cn/zh/article/doi/10.16152/j.cnki.xdxbzr.2023-03-007/
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
