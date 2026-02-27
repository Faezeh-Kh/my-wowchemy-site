---
title: "A language-parametric test amplification framework for executable domain-specific languages"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Erwan Bousse
- Jean-Marie Mottu
- Gerson Sunyé
- Djame Eddine Khelladi
- Pablo Gómez-Abajo
- Pablo C.Cañizares
- Esther Guerra
- Juan de Lara

# Author notes (optional)
author_notes:
- CNRS, University of Rennes, Rennes, France
- Nantes Université, IMT Atlantique, CNRS, LS2N, UMR 6004, Nantes, France
- Nantes Université, IMT Atlantique, CNRS, LS2N, UMR 6004, Nantes, France
- Nantes Université, IMT Atlantique, CNRS, LS2N, UMR 6004, Nantes, France
- CNRS, University of Rennes, Rennes, France
- Universidad Autónoma de Madrid, Madrid, Spain
- Universidad Complutense de Madrid, Madrid, Spain
- Universidad Autónoma de Madrid, Madrid, Spain
- Universidad Autónoma de Madrid, Madrid, Spain

date: "2025-03-10"
doi: "10.1007/s10270-025-01283-4"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Software and Systems Modeling
publication_short: Software and Systems Modeling (SoSym)

abstract: Behavioral models are important assets that must be thoroughly verified early in the design process. This can be achieved with manually-written test cases that embed carefully hand-picked domain-specific input data. However, such test cases may not always reach the desired level of quality, such as high coverage or being able to localize faults efficiently. Test amplification is an interesting emergent approach to improve a test suite by automatically generating new test cases out of existing manually-written ones. Yet, while ad-hoc test amplification solutions have been proposed for a few programming languages, no solution currently exists for amplifying the test suites of behavioral models. In order to fill this gap, we propose an automated and generic test amplification approach for executable domain-specific languages (DSLs). Hence, given an executable DSL, a conforming behavioral model, and an existing test suite, our approach synthesizes new regression test cases in three steps: (i) generating new test inputs by applying a set of generic modifiers on the existing test inputs; (ii) running the model under test with new inputs and generating assertions from the execution traces; and (iii) selecting the new test cases that increase the initial test quality. We provide a textual DSL to control and configure the amplification process, along with tool support for the whole approach atop the Eclipse GEMOC Studio. For assessment, we report on empirical evaluations over two different executable DSLs, which show improved test quality in terms of both coverage and mutation score.
#summary: 
tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: Preprint
#  url: ''
url_pdf: https://hal.science/hal-05377263v1/
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
