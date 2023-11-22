---
title: "GraspTraker: Tracking smartphone grab posture with inaudible sound"
summary: Detecting smartphone grasp posture using inaudible sound and FMCW modulation
tags:
  - Mobile Sensing
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ""
  focal_point: Smart

url_code: ''
url_pdf: 'https://sjlee.info/uploads/CS442.pdf'
url_slides: 'https://sjlee.info/uploads/CS442_slides.pdf'
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
<i>Course project in KAIST Mobile Computing and Applications course (CS442)</i>

<br>

## Project Summary

<p style="text-align:justify">
Mobile devices are utilized in various user contexts, which depend on the user's type and the specific situation. To optimize the user experience on mobile devices, the interaction method should be capable of recognizing and adapting to the user's context in real-time. Particularly, for common smartphones, the user's hand posture is a crucial element in the user context, given that touch is the predominant interaction method. In response to this need, we introduce GraspTracker, a system designed to track the user's hand posture in real-time using built-in sensors.

GraspTracker functions by generating a Frequency Modulated Continuous Wave (FMCW) audio signal from the smartphone's earpiece speaker and recording the sound with two distinct microphones. Subsequently, for each recorded sound, a Fast Fourier Transform (FFT) is applied to obtain the frequency response and extract features from the results. Finally, GraspTracker classifies the user's grasp posture based on the extracted features.
</p>

<br>

## Libraries & Frameworks

- Arduino
- Python (scikit-learn)