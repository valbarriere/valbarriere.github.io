---
title: '[FOUND] [Tesis pre/postgrado] [Pagada] Aprender a aprender -- IA y Meta-learning para datos Satelitales'

date: '2025-01-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-01T00:00:00Z'

# Summary. An optional shortened abstract.
summary: Tesista pagado sobre un tema interesante en un proyecto de investigacion grande!  

tags:
  - Remote Sensing
  - Multimodality

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: ..

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - deepcrop
---

Recent trend in Deep Learning is to train in a self-supervised way models that create high-quality dense vector representation to be fine-tuned on downstream tasks, allowing to reach high results in text [1], computer vision [2] but also in speech [3]. This trend is also true when processing Remote Sensing data [4], [5], [6]. These models are pre-trained on a huge quantity of data without labels using techniques such as Masked Image Modeling  of the U-BARN [7]. They have been shown to reach higher results than the state-of-the-art approach for crop classification. Moreover, recent work [8] showed that they can also be pre-train using meta-learning methods, with available labeled data in order to adapt easily to a new unseen task with only a few training examples. 

![metalearning](metalearning.png "METEOR model learned using Meta learning and various tasks from [8]")

Therefore, the development of state-of-the-art classification and estimation models, as well as technologies to collect necessary in-situ (ground truth) data, are crucially lacking in Chile. Importantly, given the violent climate changes and drought episodes Chile is currently facing, this technology is becoming imperative. In the project we describe below we propose an innovative way of developing such a technology, based on state-of-the-art deep learning models and remote sensing, that can efficiently, quickly and accurately generate estimates of field areas, crop types and yield estimations. 

### Task

Intensive pre-training of models of billions of parameters will be implemented, and we will further fine-tune them over several task using labels from chilean landsape delivered from our project partner the Centro de Información de Recursos Naturales (CIREN).  

* Collect a huge dataset of open-source Sentinel2 data at the level of the whole country and for several years 
* Train a foundational model in an auto-supervised way using the various spectrum of data from Chile (climate, vegetation, soil is very different)
* Use meta-learning algorithm in order to fine-tune the model for a broad set of different tasks using annotated dataset from Chile and from abroad
* Deliver the model as an open-source tool for the community

### Bibliography

[1]  J. Devlin, M. Chang, K. Lee, and K. Toutanova, ‘BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding’, 2018. 
[2]  A. Dosovitskiy et al., ‘An image is worth 16x16 words: Transformers for image recognition at scale’, arXiv preprint arXiv:2010.11929, 2020.  
[3]  V. Pratap et al., ‘Scaling speech technology to 1,000+ languages’, arXiv preprint arXiv:2305.13516, 2023.  
[4]  M. J. Smith, L. Fleming, and J. E. Geach, ‘EarthPT: a foundation model for Earth Observation’, arXiv preprint arXiv:2309.07207, 2023.  
[5]  A. Lacoste et al., ‘Geo-bench: Toward foundation models for earth monitoring’, Adv Neural Inf Process Syst, vol. 36, 2024.  
[6]  Z. Xiong, Y. Wang, F. Zhang, and X. X. Zhu, ‘One for All: Toward Unified Foundation Models for Earth Vision’, arXiv preprint arXiv:2401.07527, 2024.  
[7]  I. Dumeur, S. Valero, and J. Inglada, ‘Self-supervised spatio-temporal representation learning of Satellite Image Time Series’, IEEE J Sel Top Appl Earth Obs Remote Sens, 2024.
[8]  M. Rußwurm, S. Wang, B. Kellenberger, R. Roscher, and D. Tuia, ‘Meta-learning to address diverse Earth observation problems across resolutions’, Commun Earth Environ, vol. 5, no. 1, p. 37, 2024.  