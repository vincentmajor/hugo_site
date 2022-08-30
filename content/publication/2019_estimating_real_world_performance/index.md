---
title: "Estimating Real World Performance of a Predictive Model: A Case-Study in Predicting End-of-Life"
authors:
- vincent
- Neil Jethani
- Yindalon Aphinyanaphongs
date: "2019-10-22T00:00:00Z"
doi: "https://doi.org/10.1093/jamiaopen/ooaa008"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2", "3"]

# Publication name and optional abbreviated publication name.
publication: "JAMIA Open"
publication_short: ""

abstract: "
**Objective**: 
One primary consideration when developing predictive models is downstream effects on future model performance. We conduct experiments to quantify the effects of experimental design choices, namely cohort selection and internal validation methods, on (estimated) real-world model performance.<br>
**Materials and Methods**:
Four years of hospitalizations are used to develop a 1-year mortality prediction model (composite of death or initiation of hospice care). Two common methods to select appropriate patient visits from their encounter history (backwards-from-outcome and forwards-from-admission) are combined with 2 testing cohorts (random and temporal validation). Two models are trained under otherwise identical conditions, and their performances compared. Operating thresholds are selected in each test set and applied to a “real-world” cohort of labeled admissions from another, unused year.<br>
**Results**:
Backwards-from-outcome cohort selection retains 25% of candidate admissions (n = 23 579), whereas forwards-from-admission selection includes many more (n = 92 148). Both selection methods produce similar performances when applied to a random test set. However, when applied to the temporally defined “real-world” set, forwards-from-admission yields higher areas under the ROC and precision recall curves (88.3% and 56.5% vs. 83.2% and 41.6%).<br>
**Discussion**:
A backwards-from-outcome experiment manipulates raw training data, simplifying the experiment. This manipulated data no longer resembles real-world data, resulting in optimistic estimates of test set performance, especially at high precision. In contrast, a forwards-from-admission experiment with a temporally separated test set consistently and conservatively estimates real-world performance.<br>
**Conclusion**:
Experimental design choices impose bias upon selected cohorts. A forwards-from-admission experiment, validated temporally, can conservatively estimate real-world performance."

# Summary. An optional shortened abstract.
#summary: 

tags:
- Machine Learning 
- End-of-life 
featured: false

url_pdf: 'https://academic.oup.com/jamiaopen/article/3/2/243/5825387'
links:
#- name: Custom Link
- name: "PMC"
  url: "https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7382635/"
- name: "Preprint"
  url: "https://www.medrxiv.org/content/medrxiv/early/2019/10/22/19008821.full-text.pdf"
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

