---
title: 'How does a Pre-Trained Transformer Integrate Contextual Keywords? Application to Humanitarian Computing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Guillaume Jacquet

date: '2021-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 18th ISCRAM Conference*
publication_short: In *ISCRAM 21*

abstract: "In a classification task, dealing with text snippets and metadata usually requires to deal with multimodal approaches. When those metadata are textual, it is tempting to use them intrinsically with a pre-trained transformer, in order to leverage the semantic information encoded inside the model. This paper describes how to improve a humanitarian
classification task by adding the crisis event type to each tweet to be classified. Based on additional experiments of
the model weights and behavior, it identifies how the proposed neural network approach is partially over-fitting the
particularities of the Crisis Benchmark, to better highlight how the model is still undoubtedly learning to use and
take advantage of the metadata’s textual semantics."

# Summary. An optional shortened abstract.
summary: It is possible to integrate textual metadata into transformers in order to help the model improve its performances. We show the model uses the semantics of the keyword metadata analyzing the attention interaction between the metadata and the text to classify. We applied this to a humanitarian classification task over tweets, using the disaster event type as context, and finally show this method is also useful to caracterize a new event like a hurricane in a data-driven way. 

tags:
  - Natural Language Processing

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://idl.iscram.org/files/valentinbarriere/2021/2371_ValentinBarriere+GuillaumeJacquet2021.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'Oral_ISCRAM21.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Tokens interacting the most with the event type ’hurricane’ are related to the type of disaster, proper names, and the classes of the task.'
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

It is possible to integrate textual metadata into transformers in order to help the model improve its performances. We show the model uses the semantics of the keyword metadata analyzing the attention interaction between the metadata and the text to classify. We applied this to a humanitarian classification task over tweets, using the disaster event type as context, and finally show this method is also useful to caracterize a new event like a hurricane in a data-driven way. 

