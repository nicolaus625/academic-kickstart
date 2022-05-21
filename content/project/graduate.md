---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Research & implementation of Chinese
flute playing technique recognition based on
machine learning"
subtitle: ""
summary: ""
authors: []
tags: ["MIR", "Deep Learning", "Sound Event Detection"]
categories: []
date: 2020-09-02T00:21:10+08:00
lastmod: 2020-09-02T00:21:10+08:00
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
projects: []
---
- Feb. 2020 – May 2020. Beijing, CHN.
- One of the graduation theses that awarded the outstanding <a href='../../files/毕设论文.pdf' target='_blank'>paper</a> honor of School of Mathematical Science, Peking University.
- Research Assistant for prof. CHEN Xiaoou in Wangxuan Institute of Computer Technology at Peking University. 

Music object recognition and recording is the essential component of music information retrieval. Different from other fields of melody extraction and music transcription, the research on musical instrument technique detection is still in the early stage. The existing work mainly focuses on technique detection of individual notes or frame, and there is a lack of effective data set. 

This article constructed <a href='https://pan.baidu.com/s/1Czf6ZYqkW1EEpZeJh_3_gw' target='_blank'>audio dataset</a>(extraction code "jvbk" if needed) on ten kinds of techniques of transverse Chinese bamboo flute (Di), with 101 minutes of audio, using Mel frequency spectrum as audio feature, and put forward a model based on the fully convolutional neural network (FCNN). This model is an end-to-end sound event detector for variable length of the input and can be used in the detection of
instruments technology. 

Compared to the model based on VGG13, VGG16 and LeNet-5 baseline to evaluate the effectiveness of the proposed framework, this model got the average accuracy 94%, much better than all the others, on input of the different length of audio, which suggest good generalization ability. 

Key Words： sound event detection, music information retrieval, fully convolutional neural network, musical instrumet technique detection