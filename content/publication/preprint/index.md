---
title: "An example preprint / working paper"
authors:
- admin
- Felipe Feitosa
- Gabriel Kreiman

date: "2019-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Is AI fun? HumorDB: a curated dataset and benchmark to investigate graphical humor"
publication_short: "HumorDB"

abstract: Despite significant advancements in computer vision, understanding complex scenes, particularly those involving humor, remains a substantial challenge. This paper introduces HumorDB, a novel image-only dataset specifically designed to advance visual humor understanding. HumorDB consists of meticulously curated image pairs with contrasting humor ratings, emphasizing subtle visual cues that trigger humor and mitigating potential biases. The dataset enables evaluation through binary classification (Funny or Not Funny), range regression (funniness on a scale from 1 to 10), and pairwise comparison tasks (Which Image is Funnier?), effectively capturing the subjective nature of humor perception. Initial experiments reveal that while vision-only models struggle, vision-language models, particularly those leveraging large language models, show promising results. HumorDB also shows potential as a valuable zero-shot benchmark for powerful large multimodal models.

# Summary. An optional shortened abstract.
summary: HumorDB is a novel dataset for benchmarking and advancing visual humor understanding in AI systems, consisting of curated image pairs with contrasting humor ratings and enabling various evaluation tasks.

tags:
- Computer Vision
- Multimodal AI
- Benchmark Datasets

featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/2406.13564
url_pdf: https://arxiv.org/pdf/2406.13564.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- HumorDB

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

This work introduces HumorDB, a novel dataset designed to advance visual humor understanding in AI systems. The dataset consists of carefully curated image pairs with contrasting humor ratings, emphasizing subtle visual cues that trigger humor while mitigating potential biases. 

Key features of HumorDB include:
- Evaluation through multiple tasks: binary classification, range regression, and pairwise comparison
- Focus on capturing the subjective nature of humor perception
- Potential as a zero-shot benchmark for large multimodal models

Our initial experiments reveal that while vision-only models struggle with humor detection, vision-language models, particularly those leveraging large language models, show promising results. This work contributes to pushing the boundaries of AI's ability to comprehend nuanced human communication, specifically in the domain of visual humor.
