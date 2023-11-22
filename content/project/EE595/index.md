---
title: Context-aware automatic video screen manipulation using trajectory tracking
summary: Manipulating Youtube interface (rotate, zoom, relay from smartphone to laptop) using user head location & orientation. Implemented head tracking using Arduino & bluetooth connection between laptop, smartphone, and Arduino
tags:
  - Mobile Sensing
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ""
  focal_point: Smart

url_code: ''
url_pdf: 'https://sjlee.info/uploads/EE595.pdf'
url_slides: 'https://sjlee.info/uploads/EE595_slides.pdf'
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
<i>Course project in KAIST Mobile Computing and Systems for Intelligent Living course (EE595)</i>

<br>

## Project Summary

<p style="text-align:justify">
Numerous people watch videos through monitor or smartphone screen. We point out the limitations of automatic screen manipulation according to the viewer's physical context when watching video through monitor. And to provide a better experience for video viewers, we present a service with context-aware 1) automatic screen size adjustment, 2) automatic screen rotation, and 3) automatic video switch between devices. We first show the improvement in trajectory tracking through hardware adjustment and integration error reduction, which leads to the improvement of the performance of our whole system. Then we describe the architecture of our system, consisting of integration of trajectory tracking, python client, web client, and mobile client. The working system is demonstrated through the linked video in the report.
</p>

<br>

<p align="center>
<iframe width="600", height="400" src="https://www.youtube.com/embed/RVQDANiRxUU">
</iframe>
</p>

<br>

## Libraries & Frameworks

- Arduino
- Android
- Firebase