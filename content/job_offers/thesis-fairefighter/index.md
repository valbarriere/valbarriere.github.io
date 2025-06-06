---
title: '[FOUND] [Tesis postgrado] [Pagada] Deteccion de Fuego en la naturaleza usando IA'

date: '2025-01-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-01T00:00:00Z'

# Summary. An optional shortened abstract.
summary: En el contexto del proyecto fAIrefighter, como desarollar IA para combatir los incendios.  

tags:
  - Wildfire
  - Computer Vision
  - Remote Sensing

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
  - fairefighter
---

Early wildfire detection is of the utmost importance to enable rapid response efforts, and thus minimize the negative impacts of wildfire spreads. To this extent, we propose to install a networks of stations composed of cameras connected to Raspberry Pi that process the images in real time in order to automatically detect smoke plumes using Computer Vision algorithms. We scrapped the web in order to create [a new database](https://arxiv.org/abs/2402.05349) of smoke plumes' sequence of images (videos). 

![overview_EWD](overview_EWD.png "Overview of the fAIrefighter solution, using object detection models to detect smoke plumes in the wild")

The challenges are various:

* The detection is currently tackled using a classical state-of-the-art object detection model (Yolov8) that do not take into account the sequentiality
* The images are processed on a light computer, this makes space to work more frugal models
* A benchmark of the SOTA models is needed
* How to improve the quality of the dataset by using bigger models offline (even though they cannot be used online) 
*  Improve the model for early detection ([an exemple](https://www.sciencedirect.com/science/article/pii/S092427162200332X))

This is a project in collaboration with the non-profit association PyroNear and the Corporacion Nacional Forestal.
