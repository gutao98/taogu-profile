---
title: Telco Big Data Analytics for City-Scale Localization
summary: In this project, we aim to predict “serendipitous” social interactions.
tags:
date: "2016-08-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
url_code: ""
url_pdf: "https://dl.acm.org/doi/10.1145/2983323.2983345"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

In this project, we analyze telco big data and deploy a context-aware coarse-to-fine regression (CCR) model in Spark/Hadoop-based telco big data platform for city-scale localization. First, we design map-matching and interpolation algorithms to encode contextual information of road networks. Second, we build a two-layer regression model to capture coarse-to-fine contextual features in a short time window for improved localization performance. In our experiments, we collect 108 GPS-associated MR records in the centroid of Shanghai city with 12 × 11 square kilometers for 30 days, and measure four important properties of real-world MR data related to localization errors: stability, sensitivity, uncertainty and missing values. 
 
This work appears in **CIKM 2016**. 