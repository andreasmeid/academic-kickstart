---
title: "Real-World Application of a Quantitative Systems Pharmacology (QSP) Model to Predict Potassium Concentrations from Electronic Health Records: A Pilot Case towards Prescribing Monitoring of Spironolactone"
authors:
- admin
- Camilo Scherkl
- Michael Metzner
- David Czock 
- Hanna M Seidling
date: "2024-08-07T00:00:00Z"
doi: "10.3390/ph17081041"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Pharmaceuticals (Basel) 2024;17*"
publication_short: ""

abstract: Quantitative systems pharmacology (QSP) models are rarely applied prospectively for decision-making in clinical practice. We therefore aimed to operationalize a QSP model for potas-sium homeostasis to predict potassium trajectories based on spironolactone administrations. For this purpose, we proposed a general workflow that was applied to electronic health records (EHR) from patients treated in a German tertiary care hospital. The workflow steps included model exploration, local and global sensitivity analyses (SA), identifiability analysis (IA) of model parameters, and specification of their inter-individual variability (IIV). Patient covariates, selected parameters, and IIV then defined prior information for the Bayesian a posteriori prediction of individual potassium trajectories of the following day. Following these steps, the successfully operationalized QSP model was interactively explored via a Shiny app. SA and IA yielded five influential and estimable parameters (extracellular fluid volume, hyperaldosteronism, mineral corticoid receptor abundance, potassium intake, sodium intake) for Bayesian prediction. The operationalized model was validated in nine pilot patients and showed satisfactory performance based on the (absolute) average fold error. This provides proof-of-principle for a Prescribing Monitoring of potassium concentrations in a hospital system, which could suggest preemptive clinical measures and therefore potentially avoid dangerous hyperkalemia or hypokalemia.

# Summary. An optional shortened abstract.
summary: This pilot case shows how a repurposed QSP model could contribute to informed decision-making in everyday clinical practice. With increasing knowledge in the actual patient course, the model updates itself in a Bayesian approach to predict, in our case, the expected potassium course for the next 24 hours, which also takes planned drug administrations into account. Thus, the model prediction could give reason to preemptively modify potassium supplementation, to modify comedication affecting potassium concentrations, to reduce the spironolactone dose or, for safety, to arrange for additional laboratory measurements. Our use case presented here shows a proof-of-principle that this is also conceptually possible with mechanistic QSP models after being operationalized for this purpose.

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://pubmed.ncbi.nlm.nih.gov/39204148/
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
