---
title: "MeToo: Sentiment Analysis using Neural Networks"
authors:
- Mohammad Ahmad
- Mohammed Azhan
- Mohammed Sajjad Jafri
date: "2020-03-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-03-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: IEEE BigMM 2020 conference
publication_short: None

abstract: In the last few years, various communication compression techniques have emerged as an indispensable tool helping to alleviate the communication bottleneck in distributed learning. However, despite the fact biased compressors often show superior performance in practice when compared to the much more studied and understood unbiased compressors, very little is known about them. In this work we study three classes of biased compression operators, two of which are new, and their performance when applied to (stochastic) gradient descent and distributed (stochastic) gradient descent. We show for the first time that biased compressors can lead to linear convergence rates both in the single node and distributed settings. Further, via a theoretical study of several synthetic and empirical distributions of communicated gradients, we shed light on why and by how much biased compressors outperform their unbiased variants. Finally, we propose a new highly performing biased compressor—combination of Top-k and natural dithering—which in our experiments outperforms all other compression techniques.


# Summary. An optional shortened abstract.
summary: In our work we report our models, their architectures and their respective performances in the Big MM Challenge MeToo. We showed how the ensemble model, which was a collection of 3 different deep learning models, and used two different sets of Embedding vocabularies performed better than the individual models. In the future, we would try to give the problem a more defined approach, given the bias in positive and negative classes for the sentiment classes, we can try to pre-process the dataset in a better way so as to accommodate all training examples, while making sure that the outputs from negative classes do not dominate over the positive outputs from the respective classes. Some other areas which could be improved include, data scraping from the attached urls to the tweets, which can be helpful to find the relevance and judge the authenticity and perform better language understanding.

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: '#'
url_code: 'https://github.com/ahmadkhan242/MeToo-'
url_dataset: 'https://www.kaggle.com/c/ieee-bigmm-data-challenge'
# url_poster: http://2018.ds3-datascience-polytechnique.fr/wp-content/uploads/2018/06/DS3-342.pdf
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://images.unsplash.com/photo-1592499879835-3a1691ab26be?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80)'
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
