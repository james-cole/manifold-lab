---
title: 'Investigating the Utility of Explainable Artificial Intelligence for Neuroimaging-Based Dementia Diagnosis and Prognosis'
authors: ['sophie_martin', An Zhao, 'jiongqi_qu', Phoebe Imms, Andrei Irimia, Frederik Barkhof, 'admin']
author_notes: ''
date: '2026-02-02T00:00:00Z'
doi: 'https://doi.org/10.1002/hbm.70456'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-02-19T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: | 
  Human Brain Mapping
publication_short: ''

abstract: |
    Artificial intelligence and neuroimaging enable accurate dementia prediction but often involve 'black box' models that can be difficult to trust. Explainable artificial intelligence (XAI) aims to provide insights into the model's decisions; however, choosing the most appropriate method is non-trivial and often context-specific. We used T1-weighted MRI to train models on two tasks: Alzheimer's disease (AD) classification (diagnosis) and predicting conversion from mild-cognitive impairment (MCI) to all-cause dementia (prognosis). We applied eleven XAI methods across two popular image classification architectures, producing visualisations of the most salient regions. We also propose a framework for interpreting explanations produced by different XAI methods and predictive models. Models achieved balanced accuracies of 81% and 67% for diagnosis and prognosis. XAI outputs highlighted brain regions relevant to AD with strong convergence across gradient-based techniques. LIME produced explanations that were most similar across architectures. Mean saliency enhanced MCI prognosis prediction when included as an additional input feature. XAI can be used to verify that models are utilising relevant features and to generate valuable measures for further analysis.

# Summary. An optional shortened abstract.
summary: 

tags:
- Interpretability
- Dementia
- Deep Learning
- Alzheimer's Disease
- Neuroimaging
featured: false

links:
# - name: ''
# url: 'https://alz-journals.onlinelibrary.wiley.com/doi/full/10.1002/alz.12948'
#url_pdf: 'https://alz-journals.onlinelibrary.wiley.com/doi/epdf/10.1002/alz.12948'
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
  caption: 'Image from publication.'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ['interpretable_dementia_prediction']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
