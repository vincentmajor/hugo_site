---
title: "Expanding the Reach of Structured EHR Data with Clinical Notes: Improving End-of-Life Prediction"
authors:
- Seda Bilaloglu
- vincent
- Himanshu Grover
- Isabel Metzger
- Yindalon Aphinyanaphongs


date: "2021-05-17T00:00:00Z"
doi: "https://doi.org/10.32473/flairs.v34i1.128545"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The International FLAIRS Conference Proceedings, 34"
publication_short: "FLAIRS-34"

abstract: "Appropriate treatment decisions and end-of-life planning for patients with serious, life-limiting disease rely on accurate prognosis estimates. Many existing methods rely on structured electronic health record data which may limit generalizability across sites and restrict performance for patients with less documented history. Clinical notes may help to 'level the playing field'. We use History and Physical (H&P) notes written within 16 hours of hospitalization to predict 60-day, all-cause mortality. We test several neural network approaches and observe little improvement over a CNN by adding bi-directional recurrence or convolutional attention. The CNN was prospectively validated against an existing system using structured data. The CNN reports higher discrimination (86.0% vs. 80.6%) and average precision (31.4% vs. 17.9%). The CNN identifies fewer patients at high-risk but 91% were under-estimated by the existing method (high-risk: 80 vs. 131 with overlap of 7). Patients of both groups do die in the following months suggesting the two approaches identify different patient phenotypes which supplement one another. The CNN model better adapts to a new hospital where many patients have little or no structured history incapacitating the existing system (high-risk: 27 vs. 1)."

# Summary. An optional shortened abstract.
summary: 

tags:
- Machine Learning 
- End-of-life
- Natural Language Processing
featured: false

links:
url_pdf: 'https://journals.flvc.org/FLAIRS/article/view/128545/130035'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'files/2021_flairs_slides.pdf'
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
