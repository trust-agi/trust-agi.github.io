---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Towards Model Extraction Attacks in GAN-based Image Translation via Domain Shift Mitigation"
authors: [Di Mi, Yanjun Zhang, Leo Yu Zhang, Shengshan Hu, Qi Zhong, Haizhuan Yuan, Shirui Pan]
date: 2024-02-20T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-15T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "The 38th Annual AAAI Conference on Artificial Intelligence (AAAI), February 20-27, 2024, Vancouver, Canada (CORE A*)"
publication_short: ""

abstract: "Model extraction attacks (MEAs) enable an attacker to replicate the functionality of a victim deep neural network (DNN) model by only querying its API service remotely, posing a severe threat to the security and integrity of pay-per-query DNN-based services. Although the majority of current research on MEAs has primarily concentrated on neural classifiers, there is a growing prevalence of image-to-image translation (I2IT) tasks in our everyday activities. However, techniques developed for MEA of DNN classifiers cannot be directly transferred to the case of I2IT, rendering the vulnerability of I2IT models to MEA attacks often underestimated. This paper unveils the threat of MEA in I2IT tasks from a new perspective. Diverging from the traditional approach of bridging the distribution gap between attacker queries and victim training samples, we opt to mitigate the effect caused by the different distributions, known as the domain shift. This is achieved by introducing a new regularization term that penalizes high-frequency noise, and seeking a flatter minimum to avoid overfitting to the shifted distribution. Extensive experiments on different image translation tasks, including image super-resolution and style transfer, are performed on different backbone victim models, and the new design consistently outperforms the baseline by a large margin across all metrics. A few real-life I2IT APIs are also verified to be extremely vulnerable to our attack, emphasizing the need for enhanced defenses and potentially revised API publishing policies."

# Summary. An optional shortened abstract.
summary: ""

tags: [active learning, graph neural networks]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 
url_code: 
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
slides: ""
---
