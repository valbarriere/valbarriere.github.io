---
title: 'A Study of Nationality Bias in Names and Perplexity using Off-the-Shelf Affect-related Tweet Classifiers'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sebastian Cifuentes

date: '2024-11-01T00:00:00Z'
doi: '10.18653/v1/2024.emnlp-main.34'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing*
publication_short: In *EMNLP 24*

abstract: "In this paper, we apply a method to quantify biases associated with named entities from various countries. We create counterfactual examples with small perturbations on target-domain data instead of relying on templates or specific datasets for bias detection. On widely used classifiers for subjectivity analysis, including sentiment, emotion, hate speech, and offensive text using Twitter data, our results demonstrate positive biases related to the language spoken in a country across all classifiers studied. Notably, the presence of certain country names in a sentence can strongly influence predictions, up to a 23% change in hate speech detection and up to a 60% change in the prediction of negative emotions such as anger. We hypothesize that these biases stem from the training data of pre-trained language models (PLMs) and find correlations between affect predictions and PLMs likelihood in English and unknown languages like Basque and Maori, revealing distinct patterns with exacerbate correlations. Further, we followed these correlations in-between counterfactual examples from a same sentence to remove the syntactical component, uncovering interesting results suggesting the impact of the pre-training data was more important for English-speaking-country names."

# Summary. An optional shortened abstract.
summary: We've developed a method to measure biases in AI models related to named entities from different countries, and our results show that the presence of certain country names can significantly influence predictions, such as hate speech detection and emotion analysis, with changes of up to 23% and 60% respectively! Our findings suggest that these biases are rooted in the pre-training data of language models, and we've uncovered interesting patterns that reveal how the language and country of origin can impact model predictions, with English-speaking country names having a particularly strong effect.

tags:
  - Fairness
  - Explainability
  - Natural Language Processing

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2024.emnlp-main.34.pdf'
url_code: 'https://github.com/valbarriere/biases_ppl/'
url_dataset: ''
url_poster: 'EMNLP2024_Affect_PPL_poster.pdf'
url_project: ''
url_slides: 'EMNLP24_Affect_PPL_Pres.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Many classifiers are biased toward names from specific countries, with more negative sentiment and detecting less hate speech.'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - Xenophobias

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

This work is driven by the results of a [previous paper](/publication/LREC24-XENOPHOBIA/) on country-level bias detection in LLMs.

