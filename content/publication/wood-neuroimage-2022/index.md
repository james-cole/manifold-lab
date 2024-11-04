---
title: 'Accurate brain‐age models for routine clinical MRI examinations'
authors:
- admin
author_notes: ''
date: '2020-02-01T00:00:00Z'
doi: '10.1016/j.neuroimage.2022.118871'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'NeuroImage'
publication_short: 'NeuroImage'

abstract: Convolutional neural networks (CNN) can accurately predict chronological age in healthy individuals from structural MRI brain scans. Potentially, these models could be applied during routine clinical examinations to detect deviations from healthy ageing, including early-stage neurodegeneration. This could have important implications for patient care, drug development, and optimising MRI data collection. However, existing brain-age models are typically optimised for scans which are not part of routine examinations (e.g., volumetric T1-weighted scans), generalise poorly (e.g., to data from different scanner vendors and hospitals etc.), or rely on computationally expensive pre-processing steps which limit real-time clinical utility. Here, we sought to develop a brain-age framework suitable for use during routine clinical head MRI examinations. Using a deep learning-based neuroradiology report classifier, we generated a dataset of 23,302 ‘radiologically normal for age’ head MRI examinations from two large UK hospitals for model training and testing (age range = 18–95 years), and demonstrate fast (< 5 s), accurate (mean absolute error [MAE] < 4 years) age prediction from clinical-grade, minimally processed axial T2-weighted and axial diffusion-weighted scans, with generalisability between hospitals and scanner vendors (Δ MAE < 1 year). The clinical relevance of these brain-age predictions was tested using 228 patients whose MRIs were reported independently by neuroradiologists as showing atrophy ‘excessive for age’. These patients had systematically higher brain-predicted age than chronological age (mean predicted age difference = +5.89 years, 'radiologically normal for age' mean predicted age difference = +0.05 years, p < 0.0001). Our brain-age framework demonstrates feasibility for use as a screening tool during routine hospital examinations to automatically detect older-appearing brains in real-time, with relevance for clinical decision-making and optimising patient pathways.

# Summary. An optional shortened abstract.
summary: Brain age can be predicted accurately from 2D T2-weighted or DWI scans.

tags:
- Brain Age
featured: false

links:
# - name: ''
# url: 'www.sciencedirect.com/science/article/pii/S1053811922000015'
url_pdf: https://www.sciencedirect.com/science/article/pii/S1053811922000015/pdfft?md5=d7ba42a52534fbccde8af426e1ca2807&pid=1-s2.0-S1053811922000015-main.pdf
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
  focal_point: ''
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
slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
