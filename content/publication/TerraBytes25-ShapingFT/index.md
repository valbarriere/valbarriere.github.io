---
title: "Shaping Fine-Tuning of Geospatial Foundation Models: Effects of Label Availability and Temporal Resolution"
authors:
- Giovanni Castiglioni
- Nicolas Isla
- Cristian Buc
- Javiera Castillo-Navarro
- Sebastien Lefevre
- admin

date: "2025-07-25T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-25T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the first Workshop on Towards global datasets and models for Earth Observation (TerraBytes 2025)*
publication_short: In *TerraBytes @ ICML 25*

abstract: "Fine-tuning foundation models is a key step in adapting them to a particular task. In the case of Geospatial Foundation Models (GFMs), fine-tuning can be particularly challenging given data scarcity both in terms of the amount of labeled data and, in the case of Satellite Image Time Series (SITS), temporal context. Under these circumstances, the optimal GFM fine-tuning strategy across different labeled data regimes remains poorly understood. In this paper, we thoroughly assess and study the performances of two different GFMs given several combinations of two data scarcity factors: the number of labeled samples and the sequence length. Specifically, we analyze the performances on a crop classification task, particularly, semantic segmentation of the Sentinel-2 images contained in the PASTIS-HD dataset. We compare GFMs to U-TAE, as a fully supervised baseline, across varying amounts of labeled data (1%, 10%, 50%, 100%) and temporal input lengths (1, 6, 15, 25 and 35). Among these explorations, we find that using a smaller learning rate for the pre-trained encoders improves performance in moderate and high data regimes (50%-100%). In contrast, full fine-tuning outperforms partial fine-tuning in very low-label settings (1%-10%). This behavior suggests a nuanced trade-off between feature reuse and adaptation that defies the intuition of standard transfer learning. The code is available [here](https://github.com/GioCastiglioni/ShapingFT)."

# Summary. An optional shortened abstract.
# summary: StandUp4AI is a new multimodal dataset for humor detection, featuring over 330 hours of stand-up comedies in seven languages. This dataset surpasses existing ones in size and diversity, and experiments show it's a valuable resource for training models, with potential for improved performance when combined with enhanced audio speech recognition methods. 

tags:
- Remote Sensing
- Geospatial Foundation Models

featured: true

links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: https://arxiv.org/pdf/2505.18903
# url_code: 'https://github.com/Standup4AI/dataset'
# url_dataset: 'https://github.com/Standup4AI/dataset'
# url_poster: 'poster.pdf'
url_project: 'DeepCrop'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Segmentations produced for three different images on two levels of label availability in all the configurations of temporal resolutions.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- DeepCrop
- Copernicus

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

This work goes directly in the context of the [DeepCrop🛰️🌾🌽](/project/DeepCrop/) and [CopernicusLAC🛰️🇪🇺](/project/Copernicus/) projects.

