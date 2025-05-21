---
title: "DeepSeek-Prover-V1.5: Harnessing Proof Assistant Feedback for Reinforcement Learning and Monte-Carlo Tree Search"
authors:
- admin
- DeepSeek AI Research Team
date: "2024-08-16T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2408.08152"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-16T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "arXiv Preprint (Under review at ICLR 2025)"
publication_short: "arXiv"

abstract: "In this paper, we introduce DeepSeek-Prover-V1.5, a novel hybrid approach combining large language models (LLMs) and Monte-Carlo tree search for automated theorem proving. We design a truncate-and-resume mechanism for proof search that integrates single-pass and multi-pass generation strategies. By implementing reinforcement learning from proof assistant feedback (RLPAF) using the GRPO algorithm, we significantly enhance the model's performance. Our approach achieves state-of-the-art results on benchmark miniF2F (63.5%) and ProofNet (25.3%), surpassing previous approaches by substantial margins."

# Summary. An optional shortened abstract.
summary: A novel hybrid approach for automated theorem proving that combines LLMs and Monte-Carlo tree search, achieving state-of-the-art results on mathematical reasoning benchmarks.

tags:
- Formal Theorem Proving
- Reinforcement Learning
- Monte-Carlo Tree Search
- Large Language Models

featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/2408.08152
url_pdf: https://arxiv.org/pdf/2408.08152.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**DeepSeek AI**](https://deepseek.ai)'
  focal_point: ""
  preview_only: false

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
slides: ""
---

DeepSeek-Prover-V1.5 represents a significant advancement in the field of automated theorem proving through the integration of large language models with sophisticated search and learning strategies.

## Key Innovations

Our approach introduces several important innovations:

1. **Hybrid LLM-MCTS Architecture**: We combine the reasoning capabilities of large language models with the structured search capabilities of Monte-Carlo Tree Search to effectively explore the solution space of mathematical proofs.

2. **Truncate-and-Resume Mechanism**: Our novel mechanism enables more efficient proof generation by intelligently managing when to continue exploring a proof path and when to try alternative approaches.

3. **Reinforcement Learning from Proof Assistant Feedback (RLPAF)**: By leveraging feedback from formal proof assistants, we train our models to produce more accurate and valid proofs.

4. **GRPO Algorithm Implementation**: Our implementation of the GRPO algorithm enables more effective training on complex mathematical reasoning tasks.

## Results

The effectiveness of our approach is demonstrated by state-of-the-art performance on two challenging benchmarks:

- miniF2F: 63.5% success rate
- ProofNet: 25.3% success rate

These results represent significant improvements over previous approaches, validating the effectiveness of our hybrid methodology for automated theorem proving.

This work is currently under review as a conference paper at ICLR 2025.