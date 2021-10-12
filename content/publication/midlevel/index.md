---
title: "Mid-Level Visual Priors Improve Generalization and Sample Efficiency for Learning Visuomotor Policies"
authors:
- admin
- Jeffrey O. Zhang
- Amir Zamir
- Silvio Savarese
- Leonidas Guibas
- Jitendra Malik

date: "2019-01-31"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Conference on Robot Learning*, in *BayLearn*"
publication_short: "In *CoRL*, in *BayLearn*"
honor: "**[Oral]**"

abstract: "How much does having **visual priors about the world** (e.g. the fact that the world is 3D) assist in learning to perform **downstream motor tasks** (e.g. delivering a package)? We study this question by integrating a generic perceptual skill set (e.g. a distance estimator, an edge detector, etc.) within a reinforcement learning framework--see Figure 1. This skill set (hereafter **mid-level perception**) provides the policy with a more processed state of the world compared to raw images. </br> We find that using a mid-level perception confers significant advantages over training end-to-end from scratch (i.e. not leveraging priors) in navigation-oriented tasks. Agents are able to generalize to situations where the from-scratch approach fails and training becomes significantly more sample efficient. However, we show that realizing these gains requires careful selection of the mid-level perceptual skills. Therefore, we refine our findings into an efficient max-coverage feature set that can be adopted in lieu of raw images. We perform our study in completely separate buildings for training and testing and compare against visually blind baseline policies and state-of-the-art feature learning methods."
abstract_short: ""

# Summary. An optional shortened abstract.
summary: 

tags:
- Robustness
featured: true

links:
- name: Project Site 
  url: "http://perceptual.actor"
url_pdf: "https://perceptual.actor/assets/main_paper.pdf"
url_code: "https://github.com/alexsax/midlevel-reps"
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: "https://youtu.be/HtefpenfxTQ"

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

