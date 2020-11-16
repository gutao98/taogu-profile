---
title: MDLdroidLite:Enabling Resource-Efficient Deep Neural Networks on Mobile Devices
summary: This project presents MDLdroidLite, our latest on-device deep learning framework to support privacy-preserving personal mobile sensing applications.
tags:
date: "2020-11-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
url_code: ""
url_pdf: "pub/paper/Paper_3_SenSys_2020.pdf"
url_slides: ""
url_video: "https://www.youtube.com/watch?v=eYIlCkyCm0w&list=PL6jLuiS6wP5ZwAn_KFmmVa3llApWWLxOv&index=2"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
This project presents MDLdroidLite, our latest on-device deep learning framework to support privacy-preserving personal mobile sensing applications. MDLdroidLite fully operates deep learning on a single commodity smartphone for both training and inference. This is essentially achieved by a novel dynamic Fast-Grow control to transform traditional DNNs into resource-efficient model structures running on a mobile device with negligible cost. Evaluations show that MDLdroidLite outperforms existing parameter adaptation methods by speeding up training convergence 2.84× to 4.88×. The backbone models in MDLdroidLite achieve parameter reduction by 28× to 50×, FLOPs reduction by 4× to 10× over a full-sized model while keeping the same accuracy level.

This framework is the world-first on-device deep learning framework with both training and inference that is fully functioned on commercial smartphones. This platform moves an important step towards the promising mobile deep learning paradigm. We will continually improve the current version and plan to make it open-source for the public in the near future.  

This work has been published in **Sensys 2020**.
