---
title: 'DeepSeek-Prover-V1.5: Harnessing Proof Assistant Feedback for Reinforcement Learning and Monte-Carlo Tree Search'
authors:
  - admin
  - Qingxing Cao
  - Xiaohu Lu
  - Wenda Li
  - Yuhuai Wu
  
author_notes:
  - "Equal contribution"
  - "Equal contribution"
  - ""
  - ""
  - ""

date: '2024-08-08T00:00:00Z'
doi: '10.48550/arXiv.2408.08152'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Under review at ICLR 2025
publication_short: Under review at ICLR 2025

abstract: This paper introduces DeepSeek-Prover-V1.5, an advanced large language model (LLM) for mathematical theorem proving with Lean 4. We employ a hybrid approach combining LLMs with Monte-Carlo Tree Search (MCTS) using a novel truncate-and-resume mechanism for proof search. Our method integrates single-pass and multi-pass generation strategies and leverages Reinforcement Learning from Proof Assistant Feedback (RLPAF) using the GRPO algorithm. DeepSeek-Prover-V1.5 achieves state-of-the-art performance of 63.5% on the miniF2F benchmark and 25.3% on ProofNet, significantly outperforming previous approaches.

# Summary. An optional shortened abstract.
summary: We introduce DeepSeek-Prover-V1.5, a hybrid approach combining LLMs with Monte-Carlo Tree Search for automated theorem proving, achieving state-of-the-art results on miniF2F and ProofNet benchmarks.

tags:
  - Formal Theorem Proving
  - Large Language Models
  - Reinforcement Learning
  - Monte-Carlo Tree Search

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
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
  caption: ''
  focal_point: ''
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

## Overview

Large language models (LLMs) have demonstrated remarkable capabilities in various reasoning tasks, but their application to formal theorem proving remains challenging. This paper introduces DeepSeek-Prover-V1.5, a specialized model for mathematical theorem proving with the Lean 4 proof assistant.

## Key Contributions

1. **Hybrid Approach**: We combine LLMs with Monte-Carlo Tree Search (MCTS) to enhance theorem proving capabilities.
2. **Truncate-and-Resume Mechanism**: Our novel proof search mechanism integrates single-pass and multi-pass generation strategies.
3. **Reinforcement Learning**: We implement Reinforcement Learning from Proof Assistant Feedback (RLPAF) using the GRPO algorithm.
4. **State-of-the-Art Performance**: DeepSeek-Prover-V1.5 achieves 63.5% on the miniF2F benchmark and 25.3% on ProofNet, significantly outperforming previous approaches.

## Methodology

Our approach addresses the challenges of long-horizon reasoning in theorem proving by breaking down the process into manageable steps through the truncate-and-resume mechanism. This allows the model to explore different proof paths efficiently while maintaining context awareness.

The integration of MCTS provides structured exploration of the proof space, while RLPAF refines the model's ability to generate valid proof steps based on feedback from the Lean 4 proof assistant.

## Results

Experimental results demonstrate that DeepSeek-Prover-V1.5 significantly outperforms previous models on both miniF2F and ProofNet benchmarks, establishing a new state-of-the-art in automated theorem proving with LLMs.

Our analysis shows that the combination of MCTS with LLM-based generation and reinforcement learning creates a powerful synergy that enhances the model's capability to tackle complex mathematical proofs.