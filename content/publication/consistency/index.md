---
title: "Robust Learning Through Cross-Task Consistency"
authors:
- admin-equal-contrib
- Amir Zamir*
- Teresa Yeo
- Oğuzhan Faith Kar
- Nikhil Cheerla
- Rohan Suri
- Zhangjie Cao
- Jitendra Malik
- Leonidas Guibas

date: "2020-06-01"
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
honor: "**[Best Paper Nominee] [Oral]**"

abstract: "Visual perception entails solving a wide set of tasks, e.g., object detection, depth estimation, etc. The predictions made for multiple tasks from the same image are not independent, and therefore, are expected to be 'consistent'. We propose a broadly applicable and fully computational method for augmenting learning with Cross-Task Consistency. The proposed formulation is based on inference-path invariance over a graph of arbitrary tasks. We observe that learning with cross-task consistency leads to more accurate predictions and better generalization to out-of-distribution inputs. This framework also leads to an informative unsupervised quantity, called Consistency Energy, based on measuring the intrinsic consistency of the system. Consistency Energy correlates well with the supervised error (r=0.67), thus it can be employed as an unsupervised confidence metric as well as for detection of out-of-distribution inputs (ROC-AUC=0.95). The evaluations are performed on multiple datasets, including Taskonomy, Replica, CocoDoom, and ApolloScape, and they benchmark cross-task consistency versus various baselines including conventional multi-task learning, cycle consistency, and analytical consistency."

# Summary. An optional shortened abstract.
summary: 

tags:
- Robustness
featured: true

links:
- name: Project Site 
  url: "https://consistency.epfl.ch/"
url_pdf: "https://consistency.epfl.ch/Cross_Task_Consistency_ARXIV2020.pdf"
url_code: "https://github.com/EPFL-VILAB/XTConsistency"
url_dataset: ''
url_poster: ''
url_project: "https://consistency.epfl.ch/"
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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

