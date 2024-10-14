---
title: Rocket Recycling with Reinforcement Learning
summary: Hovering & landing task with soft actor critic & curiosity-driven experience replay
tags:
  - Deep Learning
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ""
  focal_point: Smart

url_code: ''
url_pdf: 'https://seungjoo.com/uploads/EE488D.pdf'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
<i>Course project in KAIST Reinforcement Learning (EE488D)</i>

<br>

## Result Video

<center>
  <table border="0">
    <tr>
      <td align="center">
        <img src="uploads/hover_video.gif" alt="Hovering task" width="350" height="350">
        <br>
        Hovering task
      </td>
      <td align="center">
        <img src="uploads/landing_video.gif" alt="Landing task" width="350" height="350">
        <br>
        Landing task
      </td>
    </tr>
  </table>
</center>

<br>

## Project Summary

<p style="text-align:justify">
Implemented the Soft Actor Critic (SAC) algorithm for discrete action space. Key ideas of SAC are using entropy regularization, and a temperature parameter. Entropy represents the randomness or uncertainty in a probability distribution. Through policy entropy maximization, SAC promotes exploration and prevents premature convergence. During training, the policy's entropy is adjusted according to the predefined target entropy. SAC introduces a temperature parameter, α (alpha), to manage exploration and exploitation trade-offs. Higher values of α result in more exploration, while lower values prioritize exploitation. We made this temperature parameter as a learnable parameter.
</p>
<p style="text-align:justify">
In conventional reinforcement learning paradigms, random sampling strategies are typically employed for replay buffer management. Since the random sampling strategy does not explicitly encourage an agent to explore novel experiences, in order to maximize the information gain and training speed, we instead implemented the Curiosity-driven Experience Replay (CER) algorithm. Instead of selecting samples randomly, the CER algorithm leverages an intrinsic reward system to prioritize samples that provide the agent with the most novel information.
</p>

<br>

## Libraries & Frameworks

- Pytorch