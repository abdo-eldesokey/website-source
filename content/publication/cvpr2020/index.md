---
title: "Uncertainty-Aware CNNs for Depth Completion: Uncertainty from Beginning to End"
authors:
- Abdelrahman Eldesokey
date: "2020-06-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The IEEE Conference on Computer Vision and Pattern Recognition*
publication_short: In *CVPR2020*

abstract: We propose a novel approach to identify disturbed measurements in the input by learning an input confidence estimator in a self-supervised manner based on the normalized convolutional neural networks (NCNNs). Further, we propose a probabilistic version of NCNNs that produces a statistically meaningful uncertainty measure for the final prediction. When we evaluate our approach on the KITTI dataset for depth completion, we outperform all the existing Bayesian Deep Learning approaches in terms of prediction accuracy, quality of the uncertainty measure, and the computational efficiency. Moreover, our small network with 670k parameters performs on-par with conventional approaches with millions of parameters. These results give strong evidence that separating the network into parallel uncertainty and prediction streams leads to state-of-the-art performance with accurate uncertainty estimates. 

# Summary. An optional shortened abstract.
summary: This paper proposes a sparse depth completion approach that is uncertainty-aware. We propose a novel paradigm of learning the uncertainty of the input and propagate it through the network until the final output. Our approach can be used with other sparse problems such as sparse optical flow and time-of-flight rectification.

tags:
- Source Themes
featured: true

links:
url_Preprint: https://arxiv.org/abs/2006.03349
url_Code: 'https://github.com/abdo-eldesokey/pncnn'
url_Video: 'https://youtu.be/Iw_yk-UoKEo'
url_Slides: ''
url_Cite: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
