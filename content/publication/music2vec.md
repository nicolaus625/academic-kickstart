---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Map-music2vec: A simple and effective baseline for self-supervised music audio representation learning"
subtitle: ""
summary: ""
authors: []
tags: ["SSL", "MIR"]
categories: []
date: 2022-12-05T18:24:35+01:00
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
projects: ["mert"]
---
Abstract: The deep learning community has witnessed an exponentially growing interest in self-supervised learning (SSL). However, it still remains unexplored how to build a framework for learning useful representations of raw music waveforms in a self-supervised manner. In this work, we design Music2Vec, a framework exploring different SSL algorithmic components and tricks for music audio recordings. Our model achieves comparable results to the state-of-the-art (SOTA) music SSL model Jukebox, despite being significantly smaller with less than 2% of parameters of the latter. The model will be released on Huggingface.


- <a href="https://arxiv.org/abs/2212.02508" target="_blank">Paper link.</a>
- <a href="https://huggingface.co/m-a-p/music2vec-v1" target="_blank">Huggingface checkpoints.</a>

- Accepted by ISMIR 2022, late breaking demo.