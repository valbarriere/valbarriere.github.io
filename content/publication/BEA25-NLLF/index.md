---
title: 'Unsupervised Automatic Short Answer Grading and Essay Scoring: A Weakly Supervised Explainable Approach'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Felipe Urrutia
  - Cristian Buc
  - Roberto Araya
  - admin

date: '2025-06-05T00:00:00Z'
# doi: '10.xxx/v1/2025.2025.bea-1.13'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-06-05T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 20th Workshop on Innovative Use of NLP for Building Educational Applications (BEA 2025)*
publication_short: In *BEA @ ACL 25*

abstract:  Automatic Short Answer Grading (ASAG) refers to automated scoring of open-ended textual responses to specific questions, both in natural language form. In this paper, we propose a method to tackle this task in a setting where annotated data is unavailable. Crucially, our method is competitive with the state-of-the-art while being lighter and interpretable. We crafted a unique dataset containing a highly diverse set of questions and a small amount of answers to these questions; making it more challenging compared to previous tasks. Our method uses weak labels generated from other methods proven to be effective in this task, which are then used to train a white-box (linear) regression based on a few interpretable features. The latter are extracted expert features and learned representations that are interpretable *per se* and aligned with manual labeling. We show the potential of our method by evaluating it on a small annotated portion of the dataset, and demonstrate that its ability compares with that of strong baselines and state-of-the-art methods, comprising an LLM that in contrast to our method comes with a high computational price and an opaque reasoning process. We further validate our model on a public Automatic Essay Scoring dataset in English, and obtained competitive results compared to other unsupervised baselines, outperforming the LLM. To gain further insights of our method, we conducted an interpretability analysis revealing sparse weights in our linear regression model, and alignment between our features and human ratings.

# Summary. An optional shortened abstract.
summary: A method for unsupervised automatic short answer grading and unsupervised automatic essay scoring, that is competitive with LLM, with way less parameters, that is white box with interpretable features. 

tags:
  - Explainability
  - Natural Language Processing

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'https://aclanthology.org/2025.bea-1.13.pdf'
url_pdf: 'BEA_ACL25.pdf'
url_code: 'https://github.com/furrutiav/unasages-bea2025'
# url_dataset: 'https://huggingface.co/datasets/furrutiav/sac_nllf/tree/main'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
# url_video: 'https://aclanthology.org/2023.emnlp-main.229.mp4'



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Full process. Phase 1, Generation of Weak Labels using Unsupervised methods (Signal Clustering or through an LLM). Phase 2 domain Expert Features (EFs) extraction and Natural Language Learned Features (NLLFs) obtained from answers to Binary Subtask Questions (BSQs). Phase 3, feature selection, interpretable model training and analysis.'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

