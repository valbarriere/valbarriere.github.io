---
title: 'Debating Europe: A Multilingual Multi-Target Stance Classification Dataset of Online Debates'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Alexandra Balahur
  - Brian Ravenet

date: '2022-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-06-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the LREC 2022 workshop on Natural Language Processing for Political Sciences*
publication_short: In *PoliticalNLP @ LREC 22*

abstract: "We present a new dataset of online debates in English, annotated with stance. The dataset was scraped from the “Debating Europe” platform, where users exchange opinions over different subjects related to the European Union. The dataset is composed of 2600 comments pertaining to 18 debates related to the “European Green Deal”, in a conversational setting. After presenting the dataset and the annotated sub-part, we pre-train a model for a multilingual stance classification over the X-stance dataset before fine-tuning it over our dataset, and vice-versa. The fine-tuned models are shown to improve stance classification performance on each of the datasets, even though they have different languages, topics and targets. Subsequently, we propose to enhance the performances over “Debating Europe” with an interaction-aware model, taking advantage of the online debate structure of the platform. We also propose a semi-supervised self-training method to take advantage of the imbalanced and unlabeled data from the whole website, leading to a final improvement of accuracy by 3.4% over a Vanilla XLM-R model."

# Summary. An optional shortened abstract.
summary: A new dataset of 2,600 online debate comments has been created to improve stance classification models. Fine-tuning and semi-supervised learning can boost accuracy by 3.4% over a baseline model.

tags:
  - Stance Recognition
  - Participatory Democracy
  - Natural Language Processing
  - Social Interactions
  - Dataset

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2022.politicalnlp-1.3'
url_code: ''
url_dataset: '#todo'
url_poster: ''
url_project: ''
url_slides: 'main.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Debating Europe is a Participatory Democracy platform where users can debates on EU topics.'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
