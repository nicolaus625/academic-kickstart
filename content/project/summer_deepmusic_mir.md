---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Tempo Detection of Chinese Pop Music"
subtitle: ""
summary: ""
authors: []
tags: ["Deep Learning", "MIR"]
categories: []
date: 2020-09-02T00:21:40+08:00
lastmod: 2020-09-02T00:21:40+08:00
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
- Jun. 2020 -- Sept. 2020. Beijing, CHN.
- Summer internship in Beijing Deepmusic Technology Co. LTD

Write literature review on song tempo/speed detection.

Designing new model on tempo detection based on BiLSTM and Temporal Convolution Network(TCN) and compared them with the baselines of Librosa and MadMOM using the data provided by Renren Karaoke Company (more than 2000 songs manually marked by my colleagues).

- In the music with stable speed or with or a slightly slower ending, the accuracy of tempo recognition is above 87% without considering the double frequency (error is less than or equal to 0.01) and above 98% general accuracy (error is less than 0.1). While MadMOM less than 90%.
- The accuracy in distinguishing between three beats(three four beats, six eight beats, twelvw eight beats etc.) and four beats(four four beats etc.) is 95 percent.
- The local tempo tasks such as song's inherent shift and whether the ending slows down deserve more attention