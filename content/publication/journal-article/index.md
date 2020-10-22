---
title: "Structure Correction for Robust Volume Segmentation in Presence of Tumors"
authors:
- Pranjal Sahu
- Yiyuan Zhao
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2015-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Biomedical and Health Informatics, 2020"
publication_short: ""

abstract: CNN based lung segmentation models in absence of diverse training dataset fail to segment lung volumes in presence of severe pathologies such as large masses, scars, and tumors. To rectify this problem, we propose a multi-stage algorithm for lung volume segmentation from CT scans. The algorithm uses a 3D CNN in the first stage to obtain a coarse segmentation of the left and right lungs. In the second stage, shape correction is performed on the segmentation mask using a 3D structure correction CNN. A novel data augmentation strategy is adopted to train a 3D CNN which helps in incorporating global shape prior. Finally, the shape corrected segmentation mask is up-sampled and refined using a parallel flood-fill operation. The proposed multi-stage algorithm is robust in the presence of large nodules/tumors and does not require labeled segmentation masks for entire pathological lung volume for training. Through extensive experiments conducted on publicly available datasets such as NSCLC, LUNA, and LOLA11 we demonstrate that the proposed approach improves the recall of large juxtapleural tumor voxels by at least 15% over state-of-the-art models without sacrificing segmentation accuracy in case of normal lungs. The proposed method also meets the requirement of CAD software by performing segmentation within 5 seconds which is significantly faster than present methods.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.researchgate.net/publication/342368058_Structure_Correction_for_Robust_Volume_Segmentation_in_Presence_of_Tumors
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
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
