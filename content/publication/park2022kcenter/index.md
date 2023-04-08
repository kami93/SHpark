---
title: "K-centered Patch Sampling for Efficient Video Recognition"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Jihoon Tack
- Byeongho Heo
- Jung-Woo Ha
- Jinwoo Shin

# Author notes (optional)
# author_notes:
draft: false
date: "2022-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2018-10-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Computer Vision (ECCV) 2022*
publication_short: In *ECCV 2022*

abstract: For decades, it has been a common practice to choose a subset of video frames for reducing the computational burden of a video understanding model. In this paper, we argue that this popular heuristic might be sub-optimal under recent transformer-based models. Specifically, inspired by that transformers are built upon patches of video frames, we propose to sample patches rather than frames using the greedy K-center search, i.e., the farthest patch to what has been chosen so far is sampled iteratively. We then show that a transformer trained with the selected video patches can outperform its baseline trained with the video frames sampled in the traditional way. Furthermore, by adding a certain spatiotemporal structuredness condition, the proposed K-centered patch sampling can be even applied to the recent sophisticated video transformers, boosting their performance further. We demonstrate the superiority of our method on Something–Something and Kinetics datasets.

# Summary. An optional shortened abstract.
summary: We propose a patch sampling method, referred to as the K-centered patch sampling, which uses the greedy K-center search for video transformers.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)

url_pdf: ''
url_code: 'https://github.com/kami93/kcenter_video'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
