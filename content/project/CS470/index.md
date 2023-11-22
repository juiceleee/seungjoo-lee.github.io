---
title: "SPADE-based Line Art Colorization"
summary: SPADE-based model that colorizes a given line art image using a hint image
tags:
  - Deep learning
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ""
  focal_point: Smart

url_code: 'https://github.com/Ugness/Line-Art-Colorization-SPADE'
url_pdf: 'https://sjlee.info/uploads/CS470.pdf'
url_slides: 'https://sjlee.info/uploads/CS470_slides.pdf'
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
<i>Course project in KAIST Introduction to Artificial Intelligence course (CS470)</i>

<br>

## Project Summary

<p style="text-align:justify">
SPADE is a semantic image synthesis model designed to generate photorealistic images based on a specified semantic input. It introduces new spatially-adaptive normalization layers, addressing the issue of standard normalization layers potentially erasing semantic information and leading to suboptimal synthesized images. Recognizing the potential applicability of this model to colorization, we considered the line art and color hints as analogous to the semantic map in SPADE. Our hypothesis was that by using these inputs, the model could effectively synthesize images resembling illustrations, allowing users to colorize line art with their preferred colors.

To this end, we will deliver a SPADE-based model that colorizes a given line art image using a hint image. Instead of the semantic map the SPADE originally used, we use the line art image and hint image that consists of color patches as a semantic input. We also implement a web demo application that allows the users to use our resulting model interactively. 
</p>

<br>

## Libraries & Frameworks

- PyTorch
- Flask
- HTML/CSS