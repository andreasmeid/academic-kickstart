---
title: "A framework to build similarity-based cohorts for personalized treatment advice - a standardized, but flexible workflow with the R package SimBaCo"
authors:
- Lucas Wirbka
- Walter E. Haefeli
- admin
date: "2020-05-29T00:00:00Z"
doi: "10.1371/journal.pone.0233686"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-05-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*PLoS One, 15:*e0233686"
publication_short: ""

abstract: Along with increasing amounts of big data sources and increasing computer performance, real-world evidence from such sources likewise gains in importance. While this mostly applies to population averaged results from analyses based on the all available data, it is also possible to conduct so-called personalized analyses based on a data subset whose observations resemble a particular patient for whom a decision is to be made. Claims data from statutory health insurance companies could provide necessary information for such personalized analyses. To derive treatment recommendations from them for a particular patient in everyday care, an automated, reproducible and efficiently programmed workflow would be required. We introduce the R-package SimBaCo (Similarity-Based Cohort generation) offering a simple, but modular, and intuitive framework for this task. With the six built-in R-functions, this framework allows the user to create similarity cohorts tailored to the characteristics of particular patients. An exemplary workflow illustrates the distinct steps beginning with an initial cohort selection according to inclusion and exclusion criteria. A plotting function facilitates investigating a particular patient's characteristics relative to their distribution in a reference cohort, for example the initial cohort or the precision cohort after the data has been trimmed in accordance with chosen variables for similarity finding. Such precision cohorts allow any form of personalized analysis, for example personalized analyses of comparative effectiveness or customized prediction models developed from precision cohorts. In our exemplary workflow, we provide such a treatment comparison whereupon a treatment decision for a particular patient could be made. This is only one field of application where personalized results can directly support the process of clinical reasoning by leveraging information from individual patient data. With this modular package at hand, personalized studies can efficiently weight benefits and risks of treatment options of particular patients.

# Summary. An optional shortened abstract.
summary: SimBaCo is a highly efficient, modular tool that enables to rapidly generate precision cohorts and apply various analysis methods to them. Derived personalized results can directly support the process of clinical reasoning because they can help interpreting individual patient data in the light of former patients by weighting benefits and risks of treatment options of this particular patient. With this modular package at hand, personalized studies of comparative effectiveness or personalized prediction models can be conducted efficiently and it will be exciting to see what benefit can be expected from this currently rarely applied technique.

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0233686&type=printable
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

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
slides: []
---

{{% alert note %}}
Click the respective buttons for more information.
{{% /alert %}}

