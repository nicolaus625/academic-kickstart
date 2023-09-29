---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Learnable Front Ends Based on Temporal Modulation for Music TaggingCCF none"
subtitle: ""
summary: ""
authors: []
tags: ["MIR"]
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
projects: ["tmnn"]
---
Abstract: While end-to-end systems are becoming popular in auditory signal processing including automatic music tagging, models using raw audio as input needs a large amount of data and computational resources without domain knowledge. Inspired by the fact that temporal modulation is regarded as an essential component in auditory perception, we introduce the Temporal Modulation Neural Network (TMNN) that combines Mel-like data-driven front ends and temporal modulation filters with a simple ResNet back end. The structure includes a set of temporal modulation filters to capture long-term patterns in all frequency channels. Experimental results show that the proposed front ends surpass state-of-the-art (SOTA) methods on the MagnaTagATune dataset in automatic music tagging, and they are also helpful for keyword spotting on speech commands. Moreover, the model performance for each tag suggests that genre or instrument tags with complex rhythm and mood tags can especially be improved with temporal modulation.


<a href="https://arxiv.org/pdf/2211.15254.pdf8" target="_blank">Paper link.</a>

- Accepted by ISMIR 2023 late breaking demo.