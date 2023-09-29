---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "On the effectiveness of speech self-supervised learning for musicCCF none"
subtitle: ""
summary: ""
authors: []
tags: ["SSL", "MIR"]
categories: []
date: 2023-04-14T18:24:35+01:00
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
Abstract: Self-supervised learning (SSL) has shown promising results in various speech and natural language processing applications. However, its efficacy in music information retrieval (MIR) still remains largely unexplored. While previous SSL models pre-trained on music recordings may have been mostly closed-sourced, recent speech models such as wav2vec2.0 have shown promise in music modelling. Nevertheless, research exploring the effectiveness of applying speech SSL models to music recordings has been limited. We explore the music adaption of SSL with two distinctive speech-related models, data2vec1.0 and Hubert, and refer to them as music2vec and musicHuBERT, respectively. We train  SSL models with 95M parameters under various pre-training configurations and systematically evaluate the MIR task performances with 13 different MIR tasks. Our findings suggest that training with music data can generally improve performance on MIR tasks, even when models are trained using paradigms designed for speech. However, we identify the limitations of such existing speech-oriented designs, especially in modelling polyphonic information. Based on the experimental results, empirical suggestions are also given for designing future musical SSL strategies and paradigms.


- <a href="https://arxiv.org/pdf/2307.05161.pdf" target="_blank">Paper link.</a>
- Accepted by ISMIR 2023, Milan, Italy.
- Music2Vec can be founded at here, the link is the same as our ISMIR2022LBD demo https://huggingface.co/m-a-p/music2vec-v1 and the training code is the same as the MERT training code. But the k-means feature need to be replaced with MFCC as the information described in the paper https://github.com/yizhilll/MERT
