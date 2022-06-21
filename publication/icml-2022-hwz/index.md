---
title: "AdAUC: End-to-end Adversarial AUC Optimization Against Long-tail Problems"
authors:
- Wenzheng Hou
- Qianqian Xu
- Zhiyong Yang
- Shilong Bao
- Yuan He
- Qingming Huang

date: "2022-05-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 39 th International Conference on Machine Learning, PMLR 139, 2022."
publication_short: "ICML 2022"

abstract: It is well-known that deep learning models are vulnerable to adversarial examples.  Existing studies of adversarial training have made great progress against this challenge. As a typical trait, they often assume that the class distribution is overall balanced. However, long-tailed datasets are ubiquitous in a wide spectrum of applications, where the amount of head class instances is significantly larger than the tail classes. Under such a scenario, AUC is a much more reasonable metric than accuracy since it is insensitive toward class distribution. Motivated by this, we present an early trial to explore adversarial training methods to optimize AUC. The main challenge lies in that the positive and negative examples are tightly coupled in the objective function. As a direct result, one cannot generate adversarial examples without a full scan of the dataset. To address this issue, based on a concavity regularization scheme, we reformulate the AUC optimization problem as a saddle point problem, where the objective becomes an instance-wise function. This leads to an end-to-end training protocol. Furthermore, we provide a convergence guarantee of the proposed training algorithm. Our analysis differs from the existing studies since the algorithm is asked to generate adversarial examples by calculating the gradient of a min-max problem. Finally, the extensive experimental results show the performance and robustness of our algorithm in three long-tail datasets.


# Summary. An optional shortened abstract.
summary: <font  size="4"> Wenzheng Hou, Qianqian Xu, <strong>Zhiyong Yang</strong>, Shilong Bao, Yuan He, Qingming Huang. <font color='red'>ICML 2022</font> <font color='blue'></font>  </font>

tags:
- recent
- first

links:

url_pdf: '' 
url_code: ''
url_slides: ''
url_poster: ''
url_video: ''


featured: false
image:
  caption: ''
  focal_point: ""
  preview_only: false
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---


