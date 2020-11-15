---
title: Improving Goodput in LoRa Concurrent Transmission
summary: This paper aims to improve the energy efficiency of LoRa by enabling LoRa nodes to operate in a downclocked 'light sleep' mode for packet reception.
tags:
date: "2020-10-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
url_code: ""
url_pdf: "https://ieeexplore.ieee.org/document/9153779"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
This paper presents a window match scheme named Cantor which improves the goodput of LoRa concurrent transmission by controlling the RX window size. Cantor does not require the frequent exchange of controlling information. Instead, it introduces a novel concurrent transmission model to estimate downlink packet reception rate (PRR) with different network parameters, a regression model is used to make the result more realistic. Then we propose a simple optimization algorithm to select optimal RX window sizes in which nodes are able to receive acknowledgments. We implement and evaluate Cantor with commodity LoRa gateway and nodes, and conduct experiments in different scenarios. Experiment results show that Cantor increases the goodput by 70% and reduces energy consumption by 30% in LoRa concurrent transmissions with 48 nodes operate at a duty cycle of 20%.

This work has been published in <strong> IEEE INTERNET OF THINGS JOURNAL </strong>.

