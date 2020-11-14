---
title: Energy Saving in LoRa
summary: This paper aims to improve the energy efficiency of LoRa by enabling LoRa nodes to operate in a downclocked 'light sleep' mode for packet reception.
tags:
date: "2020-04-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
url_code: ""
url_pdf: "https://ieeexplore.ieee.org/abstract/document/9155224"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

This paper aims to improve the energy efficiency of LoRa by enabling LoRa nodes to operate in a downclocked 'light sleep' mode for packet reception. Our study reveals under-sampled LoRa chirps suffer frequency aliasing and cause ambiguity in symbol demodulation. We address this problem by leveraging an empirical observation that the hardware of LoRa radio can cause phase jitters on modulated chirps, which result in frequency leakage in the time domain. Experiment results show that LiteNap can downclock LoRa nodes to subNyquist rates for energy savings, without substantially affecting packet reception performance.

This work has been published in <strong> INFOCOM 2020 </strong>.
