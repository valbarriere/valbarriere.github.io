---
title: 'Are Text Classifiers Xenophobic? A Country-Oriented Bias Detection Method with Least Confounding Variables'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sebastian Cifuentes

date: '2024-05-01T00:00:00Z'
doi: '10.5281/zenodo.6814563'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)*
publication_short: In *LREC-COLING 24*

abstract: "Classical bias detection methods used in Machine Learning are themselves biased because of the different confounding variables implied in the assessment of the initial biases. First they are using templates that are syntactically simple and distant from the target data on which the model will deployed. Second, current methods are assessing biases in pre-trained language models or in dataset, but not directly on the fine-tuned classifier that can actually produce harms. We propose a simple method to detect the biases of a specific fine-tuned classifier on any type of unlabeled data. The idea is to study the classifier behavior by creating counterfactual examples directly on the target data distribution and quantify the amount of changes. In this work, we focus on named entity perturbations by applying a Named Entity Recognition on target-domain data and modifying them accordingly to most common names or location of a target group (gender and country), and this for several morphosynctactically different languages spoken in relation with the countries of the target groups. We used our method on two models available open-source that are likely to be deployed by industry, and on two tasks and domains. We first assess the bias of a multilingual sentiment analysis model trained over multiple-languages tweets and available open-source, and then a multilingual stance recognition model trained over several languages and assessed over English language. Finally we propose to link the perplexity of each example with the bias of the model, by looking at the change in label distribution with respect to the language of the target group. Our work offers a fine-grained analysis of the interactions between names and languages, revealing significant biases in multilingual models."

# Summary. An optional shortened abstract.
summary: Current bias detection methods in machine learning have their own biases and limitations, so we've developed a new approach that directly tests fine-tuned classifiers on real-world data to identify potential biases. Our method, which involves creating counterfactual examples by modifying named entities in target data, revealed significant biases in multilingual models, including sentiment analysis and stance recognition models, and shed light on the complex interactions between names, languages, and model predictions. Current models tend to prefer names from the countries speaking the language of the sentence, impulsing for the name IA Xenophobia.

tags:
  - Fairness
  - Natural Language Processing

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2024.lrec-main.134.pdf'
url_code: 'https://github.com/valbarriere/Bias_COLING24/'
url_dataset: ''
url_poster: 'COLING2024_AI_Xenophobia_poster.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "We used names as proxy to estimate country-level biases."
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
