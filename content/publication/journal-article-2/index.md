---
title: "Active learning-based model predictive coverage control"
authors:
- R Rickenbach,
- J Köhler,
- A Scampicchio,
- MN Zeilinger, 
- A Carron
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
#date: "2024"
#doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Automatic Control 69"
publication_short: "IEEE TAC"

abstract: The problem of coverage control, i.e., of coordinating multiple agents to optimally cover an area, arises in various applications. However, coverage applications face two major challenges. 1) dealing with nonlinear dynamics while respecting system and safety critical constraints and 2) performing the task in an initially unknown environment. We solve the coverage problem by using a hierarchical framework, in which references are calculated at a central server and passed to the agents' local model predictive control (MPC) tracking schemes. Furthermore, to ensure that the environment is actively explored by the agents a probabilistic exploration–exploitation tradeoff is deployed. In addition, we derive a control framework that avoids the hierarchical structure by integrating the reference optimization in the MPC formulation. Active learning is then performed drawing inspiration from Upper Confidence Bound (UCB) approaches. For all developed control architectures, we guarantee closed-loop constraint satisfaction and convergence to an optimal configuration. Furthermore, all methods are tested and compared on hardware using a miniature car platform.

# Summary. An optional shortened abstract.
summary: We solve the coverage problem by using two different model predictive frameworks in combination with active learning of the unknown environment. 

# tags:
# - Source Themes
# featured: false

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
