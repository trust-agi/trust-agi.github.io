---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Towards complex dynamic physics system simulation with graph neural ordinary equations"
authors: [Guangsi Shi, Daokun Zhang, Ming Jin, Shirui Pan, S Yu Philip]
author_notes:
date: 2024-04-08T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-04-08T19:47:36+11:00

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Neural Networks (NNJ)"
publication_short: ""

abstract: "The great learning ability of deep learning facilitates us to comprehend the real physical world, making learning to simulate complicated particle systems a promising endeavour both in academia and industry. However, the complex laws of the physical world pose significant challenges to the learning based simulations, such as the varying spatial dependencies between interacting particles and varying temporal dependencies between particle system states in different time stamps, which dominate particles’ interacting behavior and the physical systems’ evolution patterns. Existing learning based methods fail to fully account for the complexities, making them unable to yield satisfactory simulations. To better comprehend the complex physical laws, we propose a novel model – Graph Networks with Spatial–Temporal neural Ordinary Differential Equations (GNSTODE) – that characterizes the varying spatial and temporal dependencies in particle systems using a united end-to-end framework. Through training with real-world particle–particle interaction observations, GNSTODE can simulate any possible particle systems with high precisions. We empirically evaluate GNSTODE’s simulation performance on two real-world particle systems, Gravity and Coulomb, with varying levels of spatial and temporal dependencies. The results show that GNSTODE yields better simulations than state-of-the-art methods, showing that GNSTODE can serve as an effective tool for particle simulation in real-world applications. Our code is made available at https://github.com/Guangsi-Shi/AI-for-physics-GNSTODE."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph neural networks]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2305.12334
url_code: https://github.com/Guangsi-Shi/AI-for-physics-GNSTODE
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
