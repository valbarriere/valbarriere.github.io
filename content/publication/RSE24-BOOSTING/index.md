---
title: 'Boosting crop classification by hierarchically fusing satellite, rotational, and contextual data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Martin Claverie
  - Maja Schneider
  - Guido Lemoine
  - Raphaël d'Andrimont
author_notes:
  - "Equal Contribution"
  - "Equal Contribution"
date: '2024-04-01T00:00:00Z'
doi: '10.1016/j.rse.2024.114110'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Remote Sensing of Environment, Volume 305, 1 May 2024, 114110*
publication_short: In *Remote Sensing of Environment*

abstract: 'Accurate early-season crop type classification is crucial for the crop production estimation and monitoring of agricultural parcels. However, the complexity of the plant growth patterns and their spatio-temporal variability present significant challenges. While current deep learning-based methods show promise in crop type classification from single- and multi-modal time series, most existing methods rely on a single modality, such as satellite optical remote sensing data or crop rotation patterns. We propose a novel approach to fuse multimodal information into a model for improved accuracy and robustness across multiple crop seasons and countries. The approach relies on three modalities used: remote sensing time series from Sentinel-2 and Landsat 8 observations, parcel crop rotation and local crop distribution. To evaluate our approach, we release a new annotated dataset of 7.4 million agricultural parcels in France (FR) and the Netherlands (NL). We associate each parcel with time-series of surface reflectance (Red and NIR) and biophysical variables (LAI, FAPAR). Additionally, we propose a new approach to automatically aggregate crop types into a hierarchical class structure for meaningful model evaluation and a novel data-augmentation technique for early-season classification. Performance of the multimodal approach was assessed at different aggregation levels in the semantic domain, yielding to various ranges of the number of classes spanning from 151 to 8 crop types or groups. It resulted in accuracy ranging from 91% to 95% for the NL dataset and from 85% to 89% for the FR dataset. Pre-training on a dataset improves transferability between countries, allowing for cross- domain and label prediction, and robustness of the performances in a few-shot setting from FR to NL, i.e., when the domain changes as per with significantly new labels. Our proposed approach outperforms comparable methods by enabling deep learning methods to use the often overlooked spatio-temporal context of parcels, resulting in increased precision and generalization capacity.'

# Summary. An optional shortened abstract.
summary: This is a new approach to classify crop types using a multimodal hierarchical model combinning satellite data, crop rotation patterns, and local crop distribution. It outperforms existing approaches by leveraging the spatio-temporal context of agricultural parcels, and has shown promising results in cross-country transferability and few-shot learning settings.

tags:
  - Remote Sensing
  - Computer Vision
  - Multimodality

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0034425724001214'
url_code: 'https://github.com/valbarriere/RSE_CropDeepHierarchical'
url_dataset: 'https://jeodpp.jrc.ec.europa.eu/ftp/jrc-opendata/DRLL/CropDeepTrans/data/'
url_poster: ''
url_project: ''
url_slides: 'Oral_EO4AGRI.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Crop map over the 6.8m parcels of France.'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - DeepCrop
  - Copernicus

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

