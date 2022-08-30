---
title: "Development, Implementation, and Prospective Validation of a Model to Predict 60-Day End-of-Life in Hospitalized Adults Upon Admission at Three Sites"
authors:
- vincent
- Yindalon Aphinyanaphongs
date: "2020-09-7T00:00:00Z"
doi: "https://doi.org/10.1186/s12911-020-01235-6"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "BMC Medical Informatics and Decision Making"
publication_short: "BMC Med Inform Decis Mak"

abstract: "
**Background**:
Automated systems that use machine learning to estimate a patient’s risk of death are being developed to influence care. There remains sparse transparent reporting of model generalizability in different subpopulations especially for implemented systems.<br>
**Methods**:
A prognostic study included adult admissions at a multi-site, academic medical center between 2015 and 2017. A predictive model for all-cause mortality (including initiation of hospice care) within 60 days of admission was developed. Model generalizability is assessed in temporal validation in the context of potential demographic bias. A subsequent prospective cohort study was conducted at the same sites between October 2018 and June 2019. Model performance during prospective validation was quantified with areas under the receiver operating characteristic and precision recall curves stratified by site. Prospective results include timeliness, positive predictive value, and the number of actionable predictions.<br>
**Results**:
Three years of development data included 128,941 inpatient admissions (94,733 unique patients) across sites where patients are mostly white (61%) and female (60%) and 4.2% led to death within 60 days. A random forest model incorporating 9614 predictors produced areas under the receiver operating characteristic and precision recall curves of 87.2 (95% CI, 86.1–88.2) and 28.0 (95% CI, 25.0–31.0) in temporal validation. Performance marginally diverges within sites as the patient mix shifts from development to validation (patients of one site increases from 10 to 38%). Applied prospectively for nine months, 41,728 predictions were generated in real-time (median [IQR], 1.3 [0.9, 32] minutes). An operating criterion of 75% positive predictive value identified 104 predictions at very high risk (0.25%) where 65% (50 from 77 well-timed predictions) led to death within 60 days.<br>
**Conclusion**:
Temporal validation demonstrates good model discrimination for 60-day mortality. Slight performance variations are observed across demographic subpopulations. The model was implemented prospectively and successfully produced meaningful estimates of risk within minutes of admission."

# Summary. An optional shortened abstract.
summary: 

tags:
- Machine Learning 
- End-of-life 
featured: false

links:
- name: "PMC"
  url: "https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7487547/"
url_pdf: 'https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-020-01235-6'
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
