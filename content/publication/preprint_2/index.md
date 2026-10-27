---
title: "MOSAIC: Mode- and Support-Aware Inference-Time Control of Robot Diffusion Models"
authors:
- S Bodmer
- R Rickenbach
- R Zurbrügg
- MN Zeilinger
- C Jones
date: '2026-01-01'
#doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Generative policies such as diffusion models provide expressive data-driven priors for robot behavior, yet the situations a robot faces at execution time rarely match its training data and impose constraints and objectives the policy never learned. Existing inference-time guidance methods either rely on gradients that can push samples away from the learned prior, or on sampling procedures that can be inefficient, collapse modes, or average them into out-of-distribution predictions. We introduce MOSAIC, a mode- and support-aware framework for gradient-free inference-time control of robotic diffusion models. MOSAIC treats the initial noise and all stochastic reverse-step perturbations as a joint input to the pretrained denoising process and adapts a distribution over this input using importance weights computed from fully denoised outputs. Physical feasibility and consistency with the learned support are balanced using adaptive penalties, while mode-wise importance-weighted updates preserve modes and avoid destructive averaging. The same formulation can jointly steer multiple independently trained diffusion models through shared coupling costs, enabling coordinated behavior without requiring a joint model. We evaluate MOSAIC on navigation, dexterous grasping, motion planning with unseen geometry, and collaborative box manipulation with independently trained robot priors. Across these settings, MOSAIC adapts and composes frozen diffusion priors under new deployment constraints without retraining.

# Summary. An optional shortened abstract.
summary: We introduce MOSAIC, a mode- and support-aware framework for gradient-free inference-time control of robotic diffusion models, letting frozen diffusion priors adapt and compose under new deployment constraints without retraining.

tags:
- Diffusion Models
- Inference-Time Control
- Robot Learning

# featured: true

url_pdf: 'https://arxiv.org/pdf/2610.17001'

# links:
# - name: Custom Link
#   url: http://example.org
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: ''
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
