---
title: "Tackling Biases In or Using Generative AI @ JSIC'24"

event: Journée Scientifiques Inria Chile 2024
event_url: https://journeesscientifiques2024.inria.cl/

location: GAM -- Museo Gabriela Mistral
address:
#  street: 450 Serra Mall
  city: Santiago
  region: RM
  postcode: ''
  country: Chile

summary: Tackling Biases In or Using Generative AI
abstract: "We have observed cases where these systems leverage gender, race, or even socioeconomic class information inappropriately for task resolution. Instead of employing real causal reasoning, they often rely on spurious correlations—a phenomenon commonly referred to as bias. In this talk, I present the results of 4 recent papers we published in the last 12 months, discussing methods to detect biases in large language and multimodal models. After demistifying the concept of bias, we introduce a method to detect country-related biases in LLMs using name as proxy, and study the correlation with the model's language modeling power. Then, we propose a method to mitigate biases in vision-language models using data augmentation with text-to-image generation, which reduces gender bias and improves model performance in tasks like object counting and color detection."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-12-04T08:30:00Z'
date_end: '2030-12-06T17:30:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-11-27T08:00:00Z'

authors:
  - admin

tags: 
- Fairness
- Multimodality
- Stance Recognition
- Natural Language Processing

# Is this a featured talk? (true/false)
featured: true

image:
  caption: ''
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
# rl_code: 'https://github.com'
# url_pdf: ''
url_slides: 'JSIC_Biases.pdf'
url_video: 'https://youtu.be/jzpj5mBQIwE?feature=shared&t=8510'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---

In this talk, I am focusing on several methods based on data perturbation to detect biases in Large Language Models (LLMs) and Large Multimodal Models (LMMs). We have observed cases where these systems leverage gender, race, or even socioeconomic class information inappropriately for task resolution. Instead of employing real causal reasoning, they often rely on spurious correlations—a phenomenon commonly referred to as bias. 

We will demystify the concept of bias, explaining why biases are ubiquitous, why they can sometimes be useful, and proposing a method to detect harmful biases. 

First, we will introduce a method we developed to detect biases in LLMs toward different countries using the most common names as proxies. Our findings reveal very negative biases toward certain countries, using widely utilized open-source classifiers for social media analysis. Furthermore, we demonstrate that the same multilingual model tends to favor names from countries that speak the language of the sentence—a phenomenon we call AI Xenophobia. This phenomenon has significant social implications. Our study, which examined the perplexity of language models and classifier outputs, shows that the model reacts differently to completely unknown languages compared to familiar ones and exhibits similar behavior toward names as it does with unfamiliar languages. 

Second, we present a method to mitigate biases in Vision-Language Models, particularly in image captioning models. By perturbing the training data through data augmentation with a Text-to-Image generative model, we enhance variability in the dataset. This approach not only reduces gender bias but also improves the model's performance in tasks such as counting objects and detecting colors.