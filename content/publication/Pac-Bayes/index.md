---
title: "Unifying Variational Inference and PAC-Bayes for Supervised Learning that Scales"
authors:
- Sanjay Thakur
- Herke Van Hoof
- admin
- David Meger

date: "2019-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Neural  Network  based  controllers  hold  enormous  potential  to  learn complex, high-dimensional functions. However, they are prone to overfitting and unwarranted extrapolations. PAC Bayes is a generalized framework which is more resistant to overfitting and that yields performance bounds that hold with arbitrarily high probability even on the unjustified extrapolations.  However, optimizing to learn such a function and a bound is intractable for complex tasks. In this work, we propose a method to simultaneously learn such a function and estimate performance bounds that scale organically to high-dimensions, non-linear environments without making any explicit assumptions about the environment. We build our approach on a parallel that we draw between the formulations called ELBO and PACBayes when the risk metric is negative log likelihood. Through our experiments on multiple high dimensional MuJoCo locomotion tasks, we validate the correctness of our theory, show its ability to generalize better, and investigate the factors that are important for its learning.
# Summary. An optional shortened abstract.
summary: This work proposes to train models with imitation learning in such that they come with a PAC-bayes bound as a performance guarantee for the model. It connects the expressions for the PAC bayes bound and the ELBO of a stochastic predictive policy learnt through likelihood maximisation. The model is then trained by minimising the pac-bayes bound as the objective that also doubles as an error bound.

tags:
- Deep Learning

featured: False

url_pdf: https://arxiv.org/pdf/1910.10367.pdf
url_code: 'https://github.com/sanjaythakur/Unifying-VI-and-PAC-Bayes-for-Learning-that-Scales'
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://mila.quebec/en/blog/'
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

{{% alert note %}}
Click the *Cite* button above to view the bibtex.
{{% /alert %}}

