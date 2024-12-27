---
title: 'Multilingual Multi-Target Stance Recognition in Online Public Consultations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Alexandra Balahur

date: '2023-04-01T00:00:00Z'
doi: '10.3390/math11092161'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Mathematics 2023, 11(9), 2161*
publication_short: In *Mathematics*

abstract: "Machine Learning is an interesting tool for stance recognition in a large-scale context, in terms of data size, but also regarding the topics and themes addressed or the languages employed by the participants. Public consultations of citizens using online participatory democracy platforms offer this kind of setting and are good use cases for automatic stance recognition systems. In this paper, we propose to use three datasets of public consultations, in order to train a model able to classify the stance of a citizen within a text, towards a proposal or a debate question. We studied stance detection in several contexts: using data from an online platform without interactions between users, using multilingual data from online debates that are in one language, and using data from online intra-multilingual debates, which can contain several languages inside the same unique debate discussion. We propose several baselines and methods in order to take advantage of the different available data, by comparing the results of models using out-of-dataset annotations, and binary or ternary annotations from the target dataset. We finally proposed a self-supervised learning method to take advantage of unlabelled data. We annotated both the datasets with ternary stance labels and made them available."

# Summary. An optional shortened abstract.
summary: We've developed a machine learning approach to automatically recognize the opinions of citizens in online public consultations, using three datasets to train a model that can classify stances on various topics. Our work experiments with different methods, including self-supervised learning, and makes several annotated datasets available for others to use. This work was used in the Touché shared task of CLEF 2023. 

tags:
  - Stance Recognition
  - Social Interactions
  - Natural Language Processing

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.mdpi.com/2227-7390/11/9/2161'
url_code: ''
url_dataset: 'https://touche.webis.de/clef23/touche23-web/multilingual-stance-classification.html#data'
url_poster: ''
url_project: 'https://touche.webis.de/clef23/touche23-web/multilingual-stance-classification.html'
url_slides: ''
url_source: ''
url_video: 'https://drive.google.com/file/d/1ARE-Po6rWEvOkTuaCVOZpSj0Eb9qpTk8/view'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'We studied stance recognition using multilingual data from different participatory democracy platforms.'
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

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
