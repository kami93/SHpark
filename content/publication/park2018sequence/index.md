---
title: "Sequence-to-Sequence Prediction of Vehicle Trajectory via LSTM Encoder-Decoder Architecture"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- ByeongDo Kim
- Chang Mook Kang
- Jun Won Choi

# Author notes (optional)
# author_notes:
draft: false
date: "2018-06-28T00:00:00Z"
doi: "10.1109/IVS.2018.8500658"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-10-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Intelligent Vehicles Symposium (IV) 2018*
publication_short: In *IEEE IV'18*

abstract: In this paper, we propose a deep learning based vehicle trajectory prediction technique which can generate the future trajectory sequence of surrounding vehicles in real time. We employ the encoder-decoder architecture which analyzes the pattern underlying in the past trajectory using the long short-term memory (LSTM) based encoder and generates the future trajectory sequence using the LSTM based decoder. This structure produces the K most likely trajectory candidates over occupancy grid map by employing the beam search technique which keeps the K locally best candidates from the decoder output. The experiments conducted on highway traffic scenarios show that the prediction accuracy of the proposed method is significantly higher than the conventional trajectory prediction techniques.

# Summary. An optional shortened abstract.
summary: We propose a deep learning based vehicle trajectory prediction technique which can generate the future trajectory sequence of surrounding vehicles in real time.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://drive.google.com/file/d/1lznw7kD2XrR8z5TlBlWn5wtdeD6_E-JT/view'

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
