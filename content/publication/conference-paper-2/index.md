---
title: 'Time Dependent Inverse Optimal Control using Trigonometric Basis Functions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - R Rickenbach,
  - E Arcari,
  - MN Zeilinger

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

#date: '2023'
#doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *5th Annual Learning for Dynamics & Control Conference*
publication_short: In *L4DC*

abstract:  The choice of objective is critical for the performance of an optimal controller. When control requirements vary during operation, e.g. due to changes in the environment with which the system is interacting, these variations should be reflected in the cost function. In this paper we consider the problem of identifying a time dependent cost function from given trajectories. We propose a strategy for explicitly representing time dependency in the cost function, i.e. decomposing it into the product of an unknown time dependent parameter vector and a known state and input dependent vector, modelling the former via a linear combination of trigonometric basis functions. These are incorporated within an inverse optimal control framework that uses the Karush–Kuhn–Tucker (KKT) conditions for ensuring optimality, and allows for formulating an optimization problem with respect to a finite set of basis function hyperparameters. Results are shown for two systems in simulation and evaluated against state-of-the-art approaches. 

# Summary. An optional shortened abstract.
summary: In this paper we consider the problem of identifying a time dependent cost function from given trajectories.

tags:
  - Learning from demonstrations,
  - Inverse optimal control, 
  - Trigonometric basis functions

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
