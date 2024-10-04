---
title: "Pretrained Text-to-Image Diffusion Models Are Versatile Representation Learners for Control"
authors:
- admin
- Karmesh Yadav
- Yarin Gal
- Dhruv Batra
- Cong Lu
- Tim G. Rudner



date: "2024-09-01T00:00:00Z"
publishDate: "2020-09-01T00:00:00Z"

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
publication:  Accepted *NeurIPS 2024* spotlight
publication_short: Accepted *NeurIPS 2024 spotlight*

abstract: Fine-tuning vision-language foundation models has emerged as a powerful approach to leveraging internet-scale data for generalization in downstream applications. A particularly promising source of representations already used in supervised learning can be derived from pretrained diffusion models. These representations have been shown to capture both high-level semantic information about a scene and low-level spatial information. However, this potential has not yet been realized for control-based robotics tasks, which often feature vision-based tasks with language instructions. This paper presents Stable Control Representations, which uses pretrained text-to-image diffusion models as a source of vision-language representations for downstream control policies. We show that these representations are competitive on a variety of challenging simulated control benchmarks and demonstrate strong performance on tasks that require generalization to unseen objects at test time. Crucially, we show that they enable generalization on a challenging open-vocabulary navigation benchmark on which it outperforms all other pretrained approaches. Finally, to examine their robustness, we deconstruct diffusion model representations by ablating different design choices involved in extracting representations from diffusion models and presenting insights into their failure modes.


tags:
- Diffusion Models
- RL
- Representation Learning

---
