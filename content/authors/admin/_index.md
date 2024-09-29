---
# Display name
title: ""

# Name pronunciation (optional)
name_pronunciation: ""

# Full name (for SEO)
first_name: Seungjoo
last_name: Lee

# Status emoji
status:
  icon: ☕️

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role_bs: Bachelor's degree @


# role: Master's student @ <a href="https://ee.kaist.ac.kr/en/">KAIST EE</a>

# Organizations/Affiliations to show in About widget
organizations_bs:
  - name:  KAIST CS
    url: https://cs.kaist.ac.kr/

organizations:
  - name:  KAIST EE
    url: https://ee.kaist.ac.kr/en/

# Short bio (displayed in user profile at end of posts)
bio: Seungjoo Lee

# Interests to show in About widget
interests: "I am applying to PhD programs for Fall 2025!"

# Education to show in About widget
# education:
#   courses:
#     - course: PhD in Artificial Intelligence
#       institution: Stanford University
#       year: 2012
#     - course: MEng in Artificial Intelligence
#       institution: Massachusetts Institute of Technology
#       year: 2009
#     - course: BSc in Artificial Intelligence
#       institution: Massachusetts Institute of Technology
#       year: 2008

# Skills
# For available icons, see: https://wowchemy.com/docs/getting-started/page-builder/#icons
# skills:
#   - name: Technical
#     items:
#     - name: Python
#       description: ''
#       percent: 80
#       icon: python
#       icon_pack: fab
#     - name: Data Science
#       description: ''
#       percent: 100
#       icon: chart-line
#       icon_pack: fas
#     - name: SQL
#       description: ''
#       percent: 40
#       icon: database
#       icon_pack: fas
#   - name: Hobbies
#     color: '#eeac02'
#     color_border: '#f0bf23'
#     items:
#       - name: Hiking
#         description: ''
#         percent: 60
#         icon: person-hiking
#         icon_pack: fas
#       - name: Cats
#         description: ''
#         percent: 100
#         icon: cat
#         icon_pack: fas
#       - name: Photography
#         description: ''
#         percent: 80
#         icon: camera-retro
#         icon_pack: fas

# Social/Academic Networking
# For available icons, see: https://wowchemy.com/docs/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "/#contact" for contact widget.
social:
  - icon: fa-envelope
    icon_pack: fa-solid
    link: "mailto:seungjoo.lee@kaist.ac.kr"
    name: Email

  - icon: fa-twitter
    icon_pack: fa-brands
    link: https://twitter.com/seungjoo99
    name: X

  - icon: fa-graduation-cap # Alternatively, use `google-scholar` icon from `ai` icon pack
    icon_pack: fa-solid
    link: https://scholar.google.com/citations?user=OsoaE7UAAAAJ&hl=en&authuser=2
    name: Google Scholar
  # - icon: github
  #   icon_pack: fab
  #   link: https://github.com/gcushen
  - icon: fa-linkedin
    icon_pack: fa-brands
    link: https://www.linkedin.com/in/seungjoo-lee-800264236/
    name: LinkedIn
  # Link to a PDF of your resume/CV.
  # To use: copy your resume to `static/uploads/resume.pdf`, enable `ai` icons in `params.yaml`,
  # and uncomment the lines below.
  - icon: fa-file
    icon_pack: fa-regular
    link: uploads/cv.pdf
    name: CV


news:
  - exp: 🎉 Paper accepted at NeurIPS 2024
    date: Sep 2024 |
  - exp: 👨‍💻 Research intern @ Microsoft Research (Mentor <a href="https://www.cs.utexas.edu/~lili/">Lili Qiu</a>)
    date: Sep 2024 |
  - exp: ✈️ Participating EMNLP 2023 @ Singapore
    date: Dec 2023 |
  - exp: 🎉 Paper accepted at EMNLP 2023
    date: Oct 2023 |
  - exp: 🎓 Graduated from KAIST with a bachelor's degree in Computer Science with honors
    date: Aug 2022 |
  - exp: 🎉 Honorable Mention at ACM CHI 2022
    date: Mar 2022 |
  - exp: 🎉 Paper accepted at ACM CHI 2022
    date: Nov 2022 |


paper:
  - name: "FedTherapist: Mental Health Monitoring with User-Generated Linguistic Expressions on Smartphones via Federated Learning"
    venue: "EMNLP '23"
    author: Jaemin Shin, Hyungjun Yoon, <font color="#4765b6"><b>Seungjoo Lee</b></font>, Sungjoon Park, Yunxin Liu, Jinho D. Choi, Sung-Ju Lee
    pdf: https://arxiv.org/abs/2310.16538
    website: https://nmsl.kaist.ac.kr/projects/fedtherapist/
    img: uploads/fedtherapist.png
  - name: "MyDJ: Sensing Food Intakes with an Attachable on Your Eyeglass Frame"
    venue: "CHI '22"
    author: Jaemin Shin, <font color="#4765b6"><b>Seungjoo Lee</b></font>, Taesik Gong, Hyungjun Yoon, Hyunchul Roh, Andrea Bianchi, and Sung-Ju Lee
    pdf: https://dl.acm.org/doi/abs/10.1145/3491102.3502041
    website: https://nmsl.kaist.ac.kr/projects/mydj/
    video: https://www.youtube.com/watch?v=77XNl39QoEE
    award: Best Paper Honorable Mention Award (Top 5%)
    img: uploads/mydj.png
    slide: uploads/mydj_slides.pdf

demo:
  - name: "Accurate Eating Detection on a Daily Wearable Necklace"
    venue: "MobiSys '19 Demo"
    author: Jaemin Shin, Hyungjun Yoon, <font color="#4765b6"><b>Seungjoo Lee</b></font>, Sungjoon Park, Yunxin Liu, Jinho D. Choi, Sung-Ju Lee
    pdf: https://dl.acm.org/doi/10.1145/3307334.3328565
    img: uploads/necktural.png

project:
  - name: "Validating Labeling Functions in Domain Shift (Out of Domain Detection)"
    desc: "Course project in KAIST Advanced Big Data-AI Integration (EE616)"
    author: Domain shift detection using programmatic weak supervision
    pdf: https://sjlee.info/uploads/EE616.pdf
    img: uploads/EE616.png
    page: https://sjlee.info/project/ee616
    slide: uploads/EE616_slides.pdf
  - name: "Will Overly Polite Sentences Harm Model Performance? Adversarial Pragmatic Perturbation for NLP"
    desc: "Course project in KAIST Bias and Ethics in Natural Language Processing course (AI620)"
    author: Adversarial attack on LLM model with tone perturbation and its defense
    pdf: https://sjlee.info/uploads/AI620.pdf
    page: https://sjlee.info/project/ai620
    img: uploads/AI620.png
  - name: "Rocket Recycling with Reinforcement Learning"
    desc: "Course project in KAIST Reinforcement Learning (EE488D)"
    author: Hovering & landing task with soft actor critic & curiosity-driven experience replay
    page: https://sjlee.info/project/ee488d
    img: uploads/EE488D.png
    pdf: https://sjlee.info/uploads/EE488D.pdf
  - name: "Context-aware automatic video screen manipulation using trajectory tracking"
    desc: "Course project in KAIST Mobile Computing and Systems for Intelligent Living course (EE595)"
    author: Manipulating Youtube interface (rotate, zoom, relay from smartphone to laptop) using user head location & orientation. </br>Implemented head tracking using Arduino & bluetooth connection between laptop, smartphone, and Arduino
    pdf: https://sjlee.info/uploads/EE595.pdf
    img: uploads/EE595.png
    website: https://sites.google.com/view/smilelab/teaching?authuser=0
    video: https://www.youtube.com/watch?v=RVQDANiRxUU
    slide: uploads/EE595_slides.pdf
    page: https://sjlee.info/project/ee595
    award: Selected as interesting project and uploaded to the course website
  - name: "GraspTraker: Tracking smartphone grab posture with inaudible sound"
    desc: "Course project in KAIST Mobile Computing and Applications course (CS442)"
    author: Detecting smartphone grasp posture using inaudible sound and FMCW modulation
    pdf: https://sjlee.info/uploads/CS442.pdf
    img: uploads/CS442.png
    page: https://sjlee.info/project/cs442
    slide: uploads/CS442_slides.pdf
  - name: "SPADE-based Line Art Colorization"
    desc: "Course project in KAIST Introduction to Artificial Intelligence course (CS470)"
    author: SPADE-based model that colorizes a given line art image using a hint image
    pdf: https://sjlee.info/uploads/CS470.pdf
    img: uploads/CS470.png
    page: https://sjlee.info/project/cs470
    slide: uploads/CS470_slides.pdf
    code: https://github.com/Ugness/Line-Art-Colorization-SPADE
  - name: "DeltaCNN: Efficient processing of CNN inference for continuous mobile vision"
    desc: "Course project in KAIST Operating System course (CS530)"
    author: Fast calculation of convolutional layers in continuous video streams using the fact that the video scene does not change significantly
    pdf: https://sjlee.info/uploads/CS530.pdf
    img: uploads/CS530.png
    page: https://sjlee.info/project/cs530
  

    
honor:
  - name: "KAIST 2023 Winner of the Graduate of the Year Award (KAIST Board of Trustee Chairperson's Prize)"
    exp: <font color="#4765b6"><b>2nd place out of 715 students</b></font>, awarded to top 5 students (0.7%) who demonstrated outstanding performances in various activities as well as in grades. Awarded at the commencement ceremony
    org: "KAIST"
    date: "Feb 2023"
  - name: "Summa Cum Laude"
    exp: Awarded for achieving the highest academic performance among students
    org: "KAIST"
    date: "Sep 2022"
  - name: "Engineering Innovator Award"
    exp: Awarded to <font color="#4765b6"><b>5 students each semester</b></font>, who showed outstanding performance in extracurricular activities, including academic publications, entrepreneurial activities, exhibitions, and inventions
    org: "KAIST college of engineering"
    date: "Sep 2022"
  - name: "Honorable Mention Award"
    exp: Awarded to <font color="#4765b6"><b>top 5% of all submissions</b></font> in CHI 2022
    org: "ACM SIGCHI"
    date: "Mar 2022"
  - name: "U.S. Army Certificate of Appreciation"
    exp: Awarded for exemplary service during military duty, serving as a role model for others
    org: "U.S. Army"
    date: "Jul 2021"
  - name: "Dean's List"
    exp: Awarded to <font color="#4765b6"><b>top 3% among 2,900+ students</b></font> in College of Engineering
    org: "KAIST"
    date: "Fall 2019"
  - name: "Dean's List"
    exp: Awarded to <font color="#4765b6"><b>top 3% among 2,900+ students</b></font> in College of Engineering
    org: "KAIST"
    date: "Spring 2019"
  - name: "National excellence scholarship"
    exp: National scholarship to students who showed excellence
    org: "Korea Student Aid Foundation"
    date: "Fall 2018 - Fall 2019" 


# Highlight the author in author lists? (true/false)
highlight_name: true
---

I am a graduate student researcher at the <a href="https://nmsl.kaist.ac.kr/">Network & Mobile Systems Lab (NMSL)</a>, <a href="https://www.kaist.ac.kr/en/">KAIST</a>, where I work under the guidance of Professor <a href="https://sites.google.com/site/wewantsj/">Sung-Ju Lee</a>. Currently, I am a research intern at <a href="https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/">Microsoft Research</a>, mentored by <a href="https://www.cs.utexas.edu/~lili/">Lili Qiu</a>. I received an M.S. degree in Electrical Engineering from <a href="https://www.kaist.ac.kr/en/">KAIST</a> and a B.S. degree in Computer Science from the same institution.


{style="text-align: justify;"}

My research interest lies in the development of practical machine learning systems capable of real-world deployment, thereby benefiting individuals. For this, I am working on Federated Learning (FL) and ML-powered mobile sensing applications. My current research focuses on practical FL, particularly addressing label deficiency challenges.
{style="text-align: justify;"}
