---
title: 'VIGOR-MPC: Vision-Guided Objective Regulation MPC'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - J Trisovic
  - R Rickenbach
  - M Landert
  - P Minos
  - MN Zeilinger

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2026-01-01'
#doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2026 Conference on Robot Learning*
publication_short: In *CoRL*

abstract: Controlling an agent in an environment solely perceived through onboard vision is challenging; perception yields noisy, variable-length, and partially occluded context, while onboard compute is shared between perception and control, limiting the planning horizon executable in real time. We propose VIGOR-MPC, a modular student-teacher framework, agnostic to the perception pipeline, which addresses reference tracking across navigation tasks by distilling a privileged, field-of-view-aware long-horizon MPC into a computationally lightweight short-horizon MPC whose cost parameters are determined online from vision. The teacher operates in simulation with full state knowledge and a multi-trajectory formulation that guarantees the agent can stay within its field of view. The student observes only the noisy, occluded context produced by a perception module and learns, via a multi-level recurrent mapping, to infer cost parameters that aim to recover the teacher's behavior despite missing information. We evaluate VIGOR-MPC on vision-based autonomous racing in simulation and on hardware. Using only onboard perception of the track, VIGOR-MPC generalizes to tracks unseen during training and approaches the lap times of the privileged long-horizon teacher while reducing per-step computation by over 90%.

# Summary. An optional shortened abstract.
summary: We propose VIGOR-MPC, a modular student-teacher framework that distills a privileged, field-of-view-aware long-horizon MPC into a lightweight short-horizon MPC whose cost parameters are inferred online from vision.

tags:
  - Imitation Learning
  - Objective Learning
  - Learning from Demonstrations
  - Recurrent Neural Networks
  - Model Predictive Control
  - Vision-Based Control

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/pdf/2610.20333'

# Custom links (uncomment lines below)
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
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
