
---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Time-Variant Reverberation
Algorithm for Reverberation Enhancement Syetem"
subtitle: "Final project of Music Audio Programming"
summary: ""
authors: []
tags: ["Other"]
categories: []
date: 2023-05-12T22:05:06-04:00
lastmod: 2023-05-12T22:05:06-04:00
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
The reverberation algorithm is usually an LTI system. The room in the concert hall does not
change, so the response does not change over time. However, this can lead to colouration and
instability due to feedback caused by the close proximity of the microphones and speakers. Some
time-varying systems can solve this problem. This paper implements a new time-varying variable
reverberation algorithm on bela, based on a combination of delay-line, lowpass filter and comb
filter and feedback, for reverberation enhancement systems. Such systems can often be used in
electroacoustically enhanced rehearsal rooms. This particular application is briefly outlined, and
other possible applications are discussed while the shortcomings of the experimental approach are
analysed.

<a href='../../files/map.mp4' target='_blank'>Demo recoding</a>.