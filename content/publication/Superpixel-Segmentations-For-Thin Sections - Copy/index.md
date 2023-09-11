---
title: "Superpixel segmentations for thin sections: Evaluation of methods to enable the generation of machine learning training data sets"
authors:
- admin
- F Wellmann, S Virgo, M von Domarus, M Jiang, J Schmatz, B Leibe
date: "2023-01-01T00:00:00Z"
doi: https://doi.org/10.1016/j.cageo.2022.105232

author_notes:
- ""
- ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Computers & Geosciences* 
publication_short: In *Computers & Geosciences* 

abstract: "The lack of well-labeled training image data has significantly impeded the development of novel DL methods in mineral thin section images identification. However, image annotation, especially pixel-wise annotation is always a costly process. Manually creating dense semantic labels for rock thin section images has been long considered as an unprecedented challenge in view of the ubiquitous variety and complexity of minerals in thin sections. To speed up the annotation, we propose a human–computer collaborative pipeline in which superpixel segmentation is used as a boundary extractor to avoid hand delineation of instances boundaries. Thin section data sets also pose specific requirements to superpixel segmentation algorithms. The most obvious aspect is that thin section data sets contain more than just a single image, due to the combined use of plane-polarized light views and cross-polarized views at different angles. Due to this limitation, we implemented the extension of an existing algorithm, SLIC, to use multiple image layers, resulting in the adapted algorithm MultiSLIC. We evaluated several algorithms with respect to their use for the specific requirements of thin section data sets, Both qualitative and quantitative evaluation studies show an overall good performance of MultiSLIC in terms of boundary adherence and compactness of the resulting segmentation. This is an important aspect for the subsequent labeling by human annotators with a specifically designed labeling tool. We also provide a prototype of superpixel labeling tool in python."

# Summary. An optional shortened abstract.
summary: We propose a new algorithm MultiSLIC to segment cross-polarized thin section images. We benchmark different superpixel methods for petrographic thin section data sets and we integrate MultiSLIC into a human-cmputer collaborative annotation pipeline. 


tags:
- Superpixel
- Python Open Source
- AI In Geosciences
- Deep Learning
- Mineral Identification
featured: true

links:
url_pdf: https://www.sciencedirect.com/science/article/pii/S0098300422001819
url_dataset: https://data.mendeley.com/datasets/cp897djgn9/2
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: Center
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
slides: ""
---