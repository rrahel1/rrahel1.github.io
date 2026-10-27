---
title: 'Physics-Informed Learning under Mixing: How Physical Knowledge Speeds Up Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - A Scampicchio
  - LF Toso
  - R Rickenbach
  - J Anderson
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
publication: In *International Conference on Learning Representations*
publication_short: In *ICLR*

abstract: A major challenge in physics-informed machine learning is to understand how the incorporation of prior domain knowledge affects learning rates when training data is not independent and identically distributed. Focusing on empirical risk minimization with physics-informed regularization, we derive complexity-dependent bounds on the excess risk in probability and in expectation. We prove that, when the physical prior information is aligned, the learning rate improves from the (slow) Sobolev minimax rate to the (fast) optimal i.i.d. one without sample-size deflation due to data dependence.

# Summary. An optional shortened abstract.
summary: We derive complexity-dependent excess risk bounds for physics-informed regularized empirical risk minimization under non-i.i.d. data, showing that aligned physical priors recover the fast i.i.d. learning rate.

tags:
  - Physics-Informed Learning
  - Statistical Learning Theory
  - Generalization Bounds

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://proceedings.iclr.cc/paper_files/paper/2026/file/5df1d92b478716877f774b82943477b3-Paper-Conference.pdf'

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
