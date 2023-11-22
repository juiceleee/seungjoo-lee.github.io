---
title: Validating Labeling Functions in Domain Shift
summary: Domain shift detection using programmatic weak supervision
tags:
  - Deep Learning
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ""
  focal_point: Smart

url_code: ''
url_pdf: 'https://sjlee.info/uploads/EE616.pdf'
url_slides: 'https://sjlee.info/uploads/EE616_slides.pdf'
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
<i>Course project in KAIST Advanced Big Data-AI Integration (EE616)</i>

<br>

## Project Summary

<p style="text-align:justify">
Detecting domain shift and updating ML pipeline appropriately is crucial in real-world ML systems. We argue that using labeling function outputs rather than downstream model outputs is a more effective method for detecting domain shift. We propose a lightweight and simple framework that converts discrete labeling functions to continuous functions and applies density estimation method to detect outof-distribution samples in test time. We analyze the performance of our proposed approach on three real-world datasets on binary sentiment analysis task, and show that our approach is effective at detecting domain shift.
</p>

<br>

## Libraries & Frameworks

- Pytorch