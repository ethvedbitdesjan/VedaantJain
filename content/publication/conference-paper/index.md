---
title: 'QuaCer-C: Quantitative Certification of Knowledge Comprehension in LLMs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ishita Chaudhary
  - admin
  - Gagandeep Singh

date: '2024-02-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-02-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *SeTLLM@ICLR 2024*
publication_short: In *SeTLLM@ICLR*

abstract: Large Language Models (LLMs) have demonstrated impressive performance on several benchmarks. However, traditional studies do not provide formal guarantees on the performance of LLMs. In this work, we propose a novel certification framework for LLM, QuaCer-C, wherein we formally certify the knowledge-comprehension capabilities of popular LLMs. Our certificates are quantitative — they consist of high-confidence, tight bounds on the probability that the target LLM gives the correct answer on any relevant knowledge comprehension prompt. Our certificates for the Llama, Vicuna, and Mistral LLMs indicate that the knowledge comprehension capability improves with an increase in the number of parameters and that the Mistral model is less performant than the rest in this evaluation.

# Summary. An optional shortened abstract.
summary: QuaCer-C is a novel framework for quantitatively certifying the knowledge comprehension capabilities of Large Language Models, providing formal guarantees on their performance.

tags:
  - Large Language Models
  - Certification
  - Knowledge Comprehension

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: arXiv
   url: https://arxiv.org/abs/2402.15929

url_pdf: 'https://arxiv.org/pdf/2402.15929.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: QuaCer-C

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

QuaCer-C introduces a novel certification framework for Large Language Models (LLMs), addressing the lack of formal guarantees in traditional performance evaluations. This work provides quantitative certificates that offer high-confidence, tight bounds on the probability of correct answers for knowledge comprehension prompts.

Key contributions of this research include:

1. Formal specification of the knowledge comprehension property using popular knowledge graphs like Wikidata5m.
2. Modeling certification as a probability estimation problem, leveraging Clopper-Pearson confidence intervals for provable, high-confidence bounds.
3. Generation of certificates for popular LLMs including Llama 7B and 13B, Vicuna 7B and 13B, and Mistral-7B.

Our findings indicate that knowledge comprehension capability improves with an increase in the number of model parameters. Comparisons between different model classes reveal that Mistral performs less effectively than Llama and Vicuna in this evaluation.

This work contributes to the development of more reliable and verifiable AI systems, crucial for applications requiring trusted knowledge processing and comprehension.