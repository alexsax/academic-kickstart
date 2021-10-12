---
title: "Omnidata: A Scalable Pipeline for Making Multi-Task Mid-Level Vision Datasets from 3D Scans"
authors:
- admin-equal-contrib
- Ainaz Eftekhar*
- Jitendra Malik
- Amir Zamir

date: "2021-09-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Computer Vision*
publication_short: In *ICCV*
honor: ""

abstract: "The Omnidata annotator is a pipeline to resample comprehensive 3D scans from the real-world into static multi-task vision datasets. Because this is resampling is parametric, we can control or steer datasets. This enables interesting lines of research (such as looking into the effects of these different parameters). And the resampled data can be used to train strong and robust vision models (results, demo).

For example, we create a starter dataset of 14 million images sampled from 2000 scanned spaces. Familiar architectures trained on a generated starter dataset reached state-of-the-art performance on multiple common vision tasks and benchmarks, despite having seen no benchmark or non-pipeline data. The depth estimation network outperforms MiDaS and the surface normal estimation network is the first to achieve human-level performance for in-the-wild surface normal estimation (at least according to one metric on the OASIS benchmark).

With 3D scanners becoming increasingly prevalent (e.g. on iPhones and iPads), we expect 3D scans to be a rich source of data in the future. We're therefore open-sourcing everything in order to make it easier to do research with steerable datasets. The Dockerized pipeline with CLI and its (mostly Python) code, PyTorch dataloaders for the resulting data, the starter dataset, download scripts, and other utilities are available in the linked GitHub repos above."

# Summary. An optional shortened abstract.
summary: 

tags:
- Robustness
featured: true

links:
- name: Project Site 
  url: "https://omnidata.vision/"
url_pdf: "https://omnidata.vision/omnidata_main.pdf"
url_code: "https://github.com/EPFL-VILAB/omnidata-code"
url_dataset: ''
url_poster: ''
url_project: "https://omnidata.vision/"
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

