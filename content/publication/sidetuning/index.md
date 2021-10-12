---
title: "Side-Tuning: A Baseline for Network Adaptation via Additive Side Networks"
authors:
- Jeffrey O. Zhang
- admin
- Amir Zamir
- Leonidas Guibas
- Jitendra Malik

date: "2020-06-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition, IEEE*
publication_short: In *CVPR*
honor: "**[Oral]**"

abstract: "When training a neural network for a desired task, one may prefer to adapt a pre-trained network rather than start with a randomly initialized one -- due to lacking enough training data, performing lifelong learning where the system has to learn a new task while being previously trained for other tasks, or wishing to encode priors in the network via preset weights. The most commonly employed approaches for network adaptation are fine-tuning and using the pre-trained network as a fixed feature extractor, among others. <br> In this paper we propose a straightforward alternative: Side-Tuning. Side-tuning adapts a pre-trained network by training a lightweight ;'side' network that is fused with the (unchanged) pre-trained network using a simple additive process. This simple method works as well as or better than existing solutions while it resolves some of the basic issues with fine-tuning, fixed features, and several other common baselines. In particular, side-tuning is less prone to overfitting when little training data is available, yields better results than using a fixed feature extractor, and does not suffer from catastrophic forgetting in lifelong learning. We demonstrate the performance of side-tuning under a diverse set of scenarios, including lifelong learning (iCIFAR, Taskonomy), reinforcement learning, imitation learning (visual navigation in Habitat), NLP question-answering (SQuAD v2), and single-task transfer learning (Taskonomy), with consistently promising results."

# Summary. An optional shortened abstract.
summary: 

tags:
- Robustness
featured: true

links:
- name: Project Site 
  url: "https://consistency.epfl.ch/"
url_pdf: "https://arxiv.org/pdf/1912.13503"
url_code: "https://github.com/jozhang97/side-tuning"
url_dataset: ''
url_poster: ''
url_project: "http://sidetuning.berkeley.edu"
url_slides: ''
url_source: ''
url_video: ''

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

