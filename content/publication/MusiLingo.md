---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "MusiLingo: Bridging Music and Text with Pre-trained Language Models for Music Captioning and Query Response"
subtitle: ""
summary: ""
authors: []
tags: ["SSL", "MIR", "Multimodal", "datasets"]
categories: []
date: 2023-09-19T18:24:35+01:00
lastmod: 2023-09-29T18:24:35+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["musilingo"]
---
Abstract: Large Language Models (LLMs) have shown immense potential in multimodal applications, yet the convergence of textual and musical domains remains relatively unexplored. To address this gap, we present MusiLingo, a novel system for music caption generation and music-related query responses. MusiLingo employs a single projection layer to align music representations from the pre-trained frozen music audio model MERT with the frozen LLaMA language model, bridging the gap between music audio and textual contexts. We train it on an extensive music caption dataset and fine-tune it with instructional data. Due to the scarcity of high-quality music Q&A datasets, we created the MusicInstruct (MI) dataset from MusicCaps, tailored for open-ended music inquiries. Empirical evaluations demonstrate its competitive performance in generating music captions and composing music-related Q&A pairs. Our introduced dataset enables notable advancements beyond previous ones.

- <a href="https://arxiv.org/pdf/2309.08730.pdf" target="_blank">Paper link.</a>
- <a href="https://github.com/zihaod/musilingo" target="_blank">Code link.</a>
- <a href="https://huggingface.co/datasets/m-a-p/Music-Instruct/tree/main" target="_blank">Dataset link.</a>
- To be submitted to ****2023.