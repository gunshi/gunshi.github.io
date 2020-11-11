---
title: Autonomous Driving using IRL
summary: Learning from Demonstrations with Inverse Reinforcement in CARLA
tags:
- Deep Learning
- Robotics
date: "2019-05-10T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Car driving in CARLA simulator
  focal_point: Smart

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---
Autonomous Driving with Inverse Reinforcement Learning

Most RL for AD works assume a simplistic goal-directed reward function with specified terms for things like closeness to center of lane etc.
We ideally don't want to specify 10 different reward terms in our loss function and then have to tune their respective coefficients for the best tradeoff and to avoid reward hacking. IRL assumes humans/agents in the scenes in demonstrations are rational agents who are implicitly optimising some reward which is unknown to us, and that we must infer (upto some degree). As the diversity of demonstrations increases, the tendency to overfit to some unintended eccentricity decreases.
The main goal of this project was to explore whether IRL can work better than interactive imitation learning, and to make algorithmic improvements to ensure the same.

We found that while the problem was very big in scope, and involved managing to get the instable IRL algorithms that had up till then only been demonstrated to work on small state spaces. There was the additional instability from the adversarial training dynamics and CARLA simulator code that had to be hacked into to get it to parallelise over a compute cluster.

Interesting observations: we found that doing IRL was a good way to find the optimal relative weights for the different reward terms if we asked the discriminator to simply provide us with the coefficients (instead of coming up with a single scalar reward!).

Links to slides for a talk on this project: https://docs.google.com/presentation/d/1AGcBNlH7KY8BCs1n61UKNR-X-VbYdSNj_8dTMCfdUGI/edit?usp=sharing

