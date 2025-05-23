---
title: "Geometric Consistency for Self-Supervised End-to-End Visual Odometry"
authors:
- Ganesh Iyer
- J. Krishna Murthy
- admin
- K. Madhava Krishna
- Liam Paull
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2018-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-04-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *1st International Workshop on Deep Learning for Visual SLAM, CVPR 2018*
publication_short: In *CVPR Workshop*

abstract: With the success of deep learning based approaches in tackling challenging problems in computer vision, a wide range of deep architectures have recently been proposed for the task of visual odometry (VO) estimation. Most of these proposed solutions rely on supervision, which requires the acquisition of precise ground-truth camera pose information, collected using expensive motion capture systems or high-precision IMU/GPS sensor rigs. In this work, we propose an unsupervised paradigm for deep visual odometry learning. We show that using a noisy teacher, which could be a standard VO pipeline, and by designing a loss term that enforces geometric consistency of the trajectory, we can train accurate deep models for VO that do not require ground-truth labels. We leverage geometry as a self-supervisory signal and propose “Composite Transformation Constraints (CTCs)”, that automatically generate supervisory signals for training and enforce geometric consistency in the VO estimate. We also present a method of characterizing the uncertainty in VO estimates thus obtained. To evaluate our VO pipeline, we present exhaustive ablation studies that demonstrate the efficacy of end-to-end, self-supervised methodologies to train deep models for monocular VO. We show that leveraging concepts from geometry and incorporating them into the training of a recurrent neural network results in performance competitive to supervised deep VO methods.

# Summary. An optional shortened abstract.
summary: CTCNet proposed using the compositional property of transformations to self-supervise learning of visual odometry from images.

tags:
- Deep Learning
- Computer Vision

# featured: false

url_pdf: https://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w9/Iyer_Geometric_Consistency_for_CVPR_2018_paper.pdf
url_code: 'https://github.com/krrish94/CTCNet-release'
#url_dataset: '#'
url_poster: 'https://krrish94.github.io/CTCNet-release/assets/CTCNet_poster.pdf'
url_project: 'https://krrish94.github.io/CTCNet-release/'
#url_slides: ''
#url_source: '#'
#url_video: 'https://www.youtube.com/watch?v=HzewyVu8LaY'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
