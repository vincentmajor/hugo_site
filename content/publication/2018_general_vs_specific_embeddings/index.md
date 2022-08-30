---
title: "Utility of General and Specific Word Embeddings for Classifying Translational Stages of Research"
authors:
- vincent
- Alisa Surkis
- Yindalon Aphinyanaphongs
date: "2018-11-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-11-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "AMIA Annual Symposium 2018 Proceedings"
publication_short: "AMIA 2018"

abstract: Conventional text classification models make a bag-of-words assumption reducing text, fundamentally a sequence of words, into word occurrence counts per document. Recent algorithms such as word2vec and fastText are capable of learning semantic meaning and similarity between words in an entirely unsupervised manner using a contextual window and doing so much faster than previous methods. Each word is represented as a vector such that similar meaning words such as ‘strong’ and ‘powerful’ are in the same general Euclidian space. Open questions about these embeddings include their usefulness across classification tasks and the optimal set of documents to build the embeddings. In this work, we demonstrate the usefulness of embeddings for improving the state of the art in classification for our tasks and demonstrate that specific word embeddings built in the domain and for the tasks can improve performance over general word embeddings (learnt on news articles, Wikipedia or PubMed).

# Summary. An optional shortened abstract.
summary: 

tags:
- Side Project
featured: false

links:
- name: "PMC"
  url: "https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6371342/"
- name: "Preprint"
  url: "https://arxiv.org/abs/1705.06262"
#url_pdf: https://qualitysafety.bmj.com/content/qhc/early/2019/09/02/bmjqs-2019-009858.full.pdf
url_code: 'https://github.com/vincentmajor/ctsa_prediction'
url_dataset: 'https://zenodo.org/record/802965'
url_poster: ''
url_project: ''
url_slides: 'files/general_vs_specific_embeddings.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
