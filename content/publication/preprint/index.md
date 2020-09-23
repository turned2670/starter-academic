---
title: "Rnn-test: Adversarial testing framework for recurrent neural network systems"
authors:
- admin
- Yue Zhao
- Xueying Han
- Quan Zhang
- Yu Jiang
- Jiaguang Sun
date: "2019-11-11"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: While huge efforts have been investigated in the adversarial testing of convolutional neural networks (CNN), the testing for recurrent neural networks (RNN) is still limited to the classification context and leave threats for vast sequential application domains. In this work, we propose a generic adversarial testing framework RNN-Test. ... For evaluation, we apply RNN-Test on two models of common RNN structure - the PTB language model and the spell checker model. RNN-Test efficiently reduces the performance of the PTB language model by increasing its test perplexity by 58.11%, and finds numbers of incorrect behaviors of the spell checker model with the success rate of 73.44% on average. With our customization, RNN-Test using the redefined neuron coverage as guidance could achieve 35.71% higher perplexity than original strategy of DeepXplore.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/abs/1911.06155
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
