---
title: "DeltaCNN: Efficient processing of CNN inference for continuous mobile vision"
summary: Fast calculation of convolutional layers in continuous video streams using the fact that the video scene does not change significantly
tags:
  - Deep learning
  - System
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ""
  focal_point: Smart

url_code: ''
url_pdf: 'https://seungjoo.com/uploads/CS530.pdf'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
<i>Course project in KAIST Operating System course (CS530)</i>

<br>

## Project Summary

<p style="text-align:justify">
Convolutional Neural Network (CNN) models for continuous mobile vision are recently being widely deployed on various mobile applications. While it is desired to run CNN models on mobile devices to avoid exposure of privacy-sensitive mobile data, processing complex CNN models on a resource-constrained mobile device became a bottleneck in assuring model accuracy and QoE. Several studies were conducted to accelerate the processing of CNN model on a mobile device, but the state-of-the-art technology only achieves 600ms to 3500ms latency for processing a single image. To address this issue, we propose DeltaCNN, which is a system that efficiently reduces the latency of CNN inference by leveraging the sparsity of the intermediate image frames that hardware-based encoder and decoder processes. From the experimental result, DeltaCNN shows the reduced latency as the sparsity of the matrix grows, while the latency of the DeltaCNN remains higher than the legacy convolution processing. We expect the latency of the DeltaCNN to outperform the legacy processing if it is fully implemented on the hardware-based encoder layer.
</p>

<br>

## Libraries & Frameworks

- PyTorch