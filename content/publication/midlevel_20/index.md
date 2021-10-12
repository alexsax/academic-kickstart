---
title: "Robust Policies via Mid-Level Visual Representations"
authors:
- admin-equal-contrib
- Bryan Chen*
- Francis E. Lewis
- Silvio Savarese
- Jitendra Malik
- Amir Zamir
- Lerrel Pinto

date: "2020-11-31"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Conference on Robot Learning**"
publication_short: "In *CoRL*"
honor: ""

abstract: "Vision-based robotics often separates the control loop into one module for perception and a separate module for control. It is possible to train the whole system end-to-end (e.g. with deep RL), but doing it 'from scratch' comes with a high sample complexity cost and the final result is often brittle, failing unexpectedly if the test environment differs from that of training.

We study the effects of using mid-level visual representations (features learned asynchronously for traditional computer vision objectives), as a generic and easy-to-decode perceptual state in an end-to-end RL framework. Mid-level representations encode invariances about the world, and we show that they aid generalization, improve sample complexity, and lead to a higher final performance. Compared to other approaches for incorporating invariances, such as domain randomization, asynchronously trained mid-level representations scale better: both to harder problems and to larger domain shifts. In practice, this means that mid-level representations could be used to successfully train policies for tasks where domain randomization and learning-from-scratch failed. We report results on both manipulation and navigation tasks, and for navigation include zero-shot sim-to-real experiments on real robots."
abstract_short: ""

# Summary. An optional shortened abstract.
summary: 

tags:
- Robustness
featured: true

links:
- name: Project Site 
  url: "https://midlevel.berkeley.edu/"
url_pdf: "https://arxiv.org/abs/2011.06698"
url_code: "https://github.com/alexsax/robust-policies-via-midlevel-vision"
url_dataset: ''
url_poster: ''
url_project: 'https://midlevel.berkeley.edu/'
url_slides: ''
url_source: ''
url_video: "https://www.youtube.com/watch?v=frV_eGdWglw"

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
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

