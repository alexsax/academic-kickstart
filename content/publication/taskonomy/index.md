---
title: "Taskonomy: Disentangling Task Transfer Learning"
authors:
- Amir Zamir
- admin-equal-contrib
- William B. Shen*
- Jitendra Malik
- Leonidas Guibas
- Silvio Savarese

date: "2018-06-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition, IEEE*
publication_short: In *CVPR*
honor: "**[Best Paper Award] [Oral]**"

abstract: "Would having surface normals simplify the depth estimation of an image?	Do visual tasks have a relationship, or are they unrelated?	Common sense suggests that visual tasks are interdependent, implying the existence of structure among tasks. However, a proper model is needed for the structure to be actionable, e.g., to reduce the supervision required by utilizing task relationships. We therefore ask: which tasks transfer to an arbitrary target task, and how well? Or, how do we learn a set of tasks collectively, with less total supervision? These are some of the questions that can be answered by a computational model of the vision tasks space, as proposed in this paper. We explore the task structure utilizing a sampled dictionary of 2D, 2.5D, 3D, and semantic tasks, and modeling their (1st and higher order) transfer behaviors in a latent space. The product can be viewed as a computational task taxonomy (Taskonomy) and a map of the task space. We study the consequences of this structure, e.g., the emerging task relationships, and exploit them to reduce supervision demand. For instance, we show that the total number of labeled datapoints needed to solve a set of 10 tasks can be reduced to 1/4 while keeping performance nearly the same by using features from multiple proxy tasks. Users can employ a provided Binary Integer Programming solver that leverages the taxonomy to find efficient supervision policies for their own use cases."

# Summary. An optional shortened abstract.
summary: 

tags:
- Transfer Learning

featured: true

links:
- name: Project Site 
  url: "http://taskonomy.vision"
url_pdf: "https://arxiv.org/abs/1804.08328"
url_code: "http://taskonomy.vision#models"
url_dataset: "http://taskonomy.vision#data"
url_poster: ''
url_project: '' 
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

See the [main website](http://taskonomy.vision) for live demos of the API and task-specific networks, as well as pretrained models, samples from the transfer networks, and also explanations of the methodology. 