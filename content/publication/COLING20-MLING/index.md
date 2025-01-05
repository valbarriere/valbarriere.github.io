---
title: 'Improving Sentiment Analysis over non-English Tweets using Multilingual Transformers and Automatic Translation for Data-Augmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Alexandra Balahur

date: '2020-12-01T00:00:00Z'
doi: '10.18653/v1/2020.coling-main.23'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-12-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 28th International Conference on Computational Linguistics*
publication_short: In *COLING 20*

abstract: "Tweets are specific text data when compared to general text. Although sentiment analysis over tweets has become very popular in the last decade for English, it is still difficult to find huge annotated corpora for non-English languages. The recent rise of the transformer models in Natural Language Processing allows to achieve unparalleled performances in many tasks, but these models need a consequent quantity of text to adapt to the tweet domain. We propose the use of a multilingual transformer model, that we pre-train over English tweets on which we apply data-augmentation using automatic translation to adapt the model to non-English languages. Our experiments in French, Spanish, German and Italian suggest that the proposed technique is an efficient way to improve the results of the transformers over small corpora of tweets in a non-English language."

# Summary. An optional shortened abstract.
summary: We propose a technique to leverage machine translation for multilingual sentiment analysis. Appart from English, which has better models and more ressources, it is useful to translate all the tweets from every language to all the other languages and train a multilingual model over this new augmented dataset.

tags:
  - Natural Language Processing
  - Affective Computing

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2020.coling-main.23v2.pdf'
url_code: ''
url_dataset: ''
url_poster: 'COLING2020_Multilingual_tweets_poster.pdf'
url_project: ''
url_slides: 'Pres_CoP_COLING2020.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Our Data Augmentation techniques which consists in translating all the languages to all the other ones, and mix everything, helps to reach higher results.'
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


