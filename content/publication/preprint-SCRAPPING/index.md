---
title: "(Preprint) Scrapping The Web For Early Wildfire Detection: A New Annotated Dataset of Images and Videos of Smoke Plumes In-the-wild"
authors:
- Mateo Lostanlen
- Nicolas Isla
- Jose Guillen
- Felix Veith
- Cristian Buc
- admin

date: "2024-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv (submitted)"
publication_short: "Arxiv (submitted)"

abstract: "Early wildfire detection is of the utmost importance to enable rapid response efforts, and thus minimize the negative impacts of wildfire spreads. To this end, we present PyroNear-2024, a new dataset composed of both images and videos, allowing for the training and evaluation of smoke plume detection models, including sequential models. The data is sourced from: *(i)* web-scraped videos of wildfires from public networks of cameras for wildfire detection in-the-wild, *(ii)* videos from our in-house network of cameras, and *(iii)* a small portion of synthetic and real images. This dataset includes around 150,000 manual annotations on 50,000 images, covering 400 wildfires, PyroNear-2024 surpasses existing datasets in size and diversity. It includes data from France, Spain, and the United States. Finally, it is composed of both images and videos, allowing for the training and evaluation of smoke plume detection models, including sequential models. We ran cross-dataset experiments using a lightweight state-of-the-art object detection model and found out the proposed dataset is particularly challenging, with F1 score of around 60%, but more stable than existing datasets. The video part of the dataset can be used to train a lightweight sequential model, improving global recall while maintaining precision. Finally, its use in concordance with other public dataset helps to reach higher results overall. We will make both our code and data available."

# Summary. An optional shortened abstract.
summary: PyroNear-2024 is a new dataset for smoke plume detection, featuring 150,000 annotations on 50,000 images and videos of 400 wildfires from France, Spain, and the US. This dataset surpasses existing ones in size and diversity, and experiments show it's a challenging but valuable resource for training models, with potential for improved performance when combined with other datasets.

tags:
- Computer Vision
- Wildifre
- Dataset

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2402.05349
url_code: '#todo'
url_dataset: '#todo'
url_poster: 'poster.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Whole process to create the video and the image datasets PyroNear.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- fAIrefighter

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

This work goes in the context of the [fAIrefighter🧯](/project/fAIrefighter/) project.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
