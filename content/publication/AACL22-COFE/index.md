---
title: 'CoFE: A New Dataset of Intra-Multilingual Multi-target Stance Classification from an Online European Participatory Democracy Platform'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Guillaume Jacquet
  - Léo Hemamou

date: '2022-11-01T00:00:00Z'
doi: '10.18653/v1/2022.aacl-short.52'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2nd Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics and the 12th International Joint Conference on Natural Language Processing*
publication_short: In *AACL-IJCNLP 22*

abstract: "Stance Recognition over proposals is the task of automatically detecting whether a comment on a specific proposal is in favor of this proposal, against this proposal or that neither inference is likely. The dataset that we propose to use is an online debating platform inaugurated in 2021, where users can submit proposals and comment over proposals or over other comments. It contains 4.2k proposals and 20k comments focused on various topics. Every comment and proposal can come written in another language, with more than 40% of the proposal/comment pairs containing at least two languages, creating a unique intra-multilingual setting. A portion of the data (more than 7k comment/proposal pairs, in 26 languages) was annotated by the writers with a self-tag assessing whether they are in favor or against the proposal. Another part of the data (without self-tag) has been manually annotated: 1206 comments in 6 morphologically different languages (fr, de, en, el, it, hu) were tagged, leading to a Krippendorff’s α of 0.69. This setting allows defining an intra-multilingual and multi-target stance classification task over online debates."

# Summary. An optional shortened abstract.
summary: A new dataset for Stance Recognition using data from the Participatory Democracy platform of the Conference for the Future of Europe. This dataset contains highly-multilingual interactions, as the platform used Machine Translation, in the sense that users interacts in using their (different) native languages in the same thread.    

tags:
  - Stance Recognition
  - Argumentation
  - Social Interactions
  - Natural Language Processing
  - Dataset

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2022.aacl-short.52.pdf'
url_code: ''
url_dataset: 'https://touche.webis.de/clef23/touche23-web/multilingual-stance-classification.html#data'
url_poster: ''
url_project: 'https://touche.webis.de/clef23/touche23-web/multilingual-stance-classification.html'
url_slides: 'AACL_COFE_pres.pdf'
url_source: ''
url_video: 'https://drive.google.com/file/d/1ARE-Po6rWEvOkTuaCVOZpSj0Eb9qpTk8/view'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Topics distribution in the propositions, comments, and the ratio of comments over
propositions regarding the differnt topics.'
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
slides: ""
---

