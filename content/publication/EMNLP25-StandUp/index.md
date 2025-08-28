---
title: "StandUp4AI: A New Multilingual Dataset for Humor Detection in Stand-up Comedy Videos"
authors:
- admin
- Nahuel Gomez
- Leo Hemamou
- Sofia Callejas
- Brian Ravenet

date: "2025-06-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "Findings of EMNLP25"
publication_short: "EMNLP25"

abstract: "Aiming towards improving current computational models of humor detection, we propose a new multimodal dataset of stand-up comedies, in seven languages: English, French, Spanish, Italian, Portuguese, Hungarian and Czech. Our dataset of more than 330 hours, is at the time of writing the biggest available for this type of task, and the most diverse. The whole dataset is automatically annotated in laughter (from the audience), and the subpart left for model validation is manually annotated. Contrary to contemporary approaches, we do not frame the task of humor detection as a binary sequence classification, but as word-level sequence labeling, in order to take into account all the context of the sequence and to capture the continuous joke tagging mechanism typically occurring in natural conversations. As par with unimodal baselines results, we propose a method for e propose a method to enhance the automatic laughter detection based on Audio Speech Recognition errors. Our code and data are available online."

# Summary. An optional shortened abstract.
summary: StandUp4AI is a new multimodal dataset for humor detection, featuring over 330 hours of stand-up comedies in seven languages. This dataset surpasses existing ones in size and diversity, and experiments show it's a valuable resource for training models, with potential for improved performance when combined with enhanced audio speech recognition methods. 

tags:
- Multimodality
- Natural Language Processing
- Dataset

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2505.18903
url_code: 'https://github.com/Standup4AI/dataset'
# url_dataset: 'https://github.com/Standup4AI/dataset'
# url_poster: 'poster.pdf'
url_project: 'standUp'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Laughter detection as sequence labelling.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Standup

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

This work goes directly in the context of the [StandUpComedy🎤😄👏](/project/Standup/) project.

