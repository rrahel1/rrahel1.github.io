---
title: "DEMONSTRATE: Zero-shot Language to Robotic Control via Multi-task Demonstration Learning"
authors:
- R Rickenbach,
- B Lee,
- R Zurbrügg, 
- CA Alonso, 
- MN Zeilinger
#date: "2025"
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

abstract: The integration of large language models (LLMs) with control systems has demonstrated significant potential in various settings, such as task completion with a robotic manipulator. A main reason for this success is the ability of LLMs to perform in-context learning, which, however, strongly relies on the design of task examples, closely related to the target tasks. Consequently, employing LLMs to formulate optimal control problems often requires task examples that contain explicit mathematical expressions, designed by trained engineers. Furthermore, there is often no principled way to evaluate for hallucination before task execution. To address these challenges, we propose DEMONSTRATE, a novel methodology that avoids the use of LLMs for complex optimization problem generations, and instead only relies on the embedding representations of task descriptions. To do this, we leverage tools from inverse optimal control to replace in-context prompt examples with task demonstrations, as well as the concept of multitask learning, which ensures target and example task similarity by construction. Given the fact that hardware demonstrations can easily be collected using teleoperation or guidance of the robot, our approach significantly reduces the reliance on engineering expertise for designing in-context examples. Furthermore, the enforced multitask structure enables learning from few demonstrations and assessment of hallucinations prior to task execution. We demonstrate the effectiveness of our method through simulation and hardware experiments involving a robotic arm tasked with tabletop manipulation.

# Summary. An optional shortened abstract.
summary: We propose DEMONSTRATE, a novel methodology that avoids the use of LLMs for complex optimization problem generations, and instead only relies on the embedding representations of task descriptions.

tags:
- Large language models,
- Learning from demonstrations,
- Safety in language to control 

# featured: true

# links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
