---
title: "Pretrained Text-to-Image Diffusion Models Are Versatile Representation Learners for Control"
authors:
- admin
- Karmesh Yadav
- Yarin Gal
- Dhruv Batra
- Cong Lu
- Tim G. Rudner



date: "2024-09-1T00:00:00Z"
# doi: ""

# # Schedule page publish date (NOT publication's date).
# publishDate: "2020-10-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

featured: true

# Publication name and optional abbreviated publication name.
publication: In *NeurIPS 2024* spotlight
publication_short: In *NeurIPS*

abstract: Fine-tuning vision-language foundation models has emerged as a powerful approach to leveraging internet-scale data for generalization in downstream applications. A particularly promising source of representations already used in supervised learning can be derived from pretrained diffusion models. These representations have been shown to capture both high-level semantic information about a scene and low-level spatial information. However, this potential has not yet been realized for control-based robotics tasks, which often feature vision-based tasks with language instructions. This paper presents \ouralgolong, which uses pretrained text-to-image diffusion models as a source of vision-language representations for downstream control policies. We show that these representations are competitive on a variety of challenging simulated control benchmarks and demonstrate strong performance on tasks that require generalization to unseen objects at test time. Crucially, we show that they enable generalization on a challenging open-vocabulary navigation benchmark on which it outperforms all other pretrained approaches. Finally, to examine their robustness, we deconstruct diffusion model representations by ablating different design choices involved in extracting representations from diffusion models and presenting insights into their failure modes.


tags:
- Diffusion Models
- RL
- Representation Learning

# featured: true

# links:
# - name: Oral
#   url: 
# url_pdf: https://arxiv.org/abs/2007.13904.pdf
# url_code: 'https://github.com/montrealrobotics/La-MAML'
# #url_dataset: '#'
# #url_poster: '#'
# url_project: 'https://mila.quebec/en/blog/'
# #url_slides: ''
# #url_source: '#'
# url_video: 'https://www.youtube.com/watch?v=HzewyVu8LaY'

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'A pictoral depiction of the La-MAML algorithm'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []
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

