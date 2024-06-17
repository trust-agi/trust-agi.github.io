---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "PSICHIC: physicochemical graph neural network for learning protein-ligand interaction fingerprints from sequence data"
authors: [Huan Yee Koh, Anh T.N. Nguyen, Shirui Pan, Lauren T. May, Geoffrey I. Webb]
author_notes:
date: 2024-06-17T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-15T19:47:36+11:00

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Nature Machine Intelligence (NMI)"
publication_short: ""

abstract: "In drug discovery, determining the binding affinity and functional effects of small-molecule ligands on proteins is critical. Current computational methods can predict these protein-ligand interaction properties but often lose accuracy without high-resolution protein structures and falter in predicting functional effects. We introduce PSICHIC (PhySIcoCHemICal graph neural network), a framework uniquely incorporating physicochemical constraints to decode interaction fingerprints directly from sequence data alone. This enables PSICHIC to attain first-of-its-kind emergent capabilities in deciphering mechanisms underlying protein-ligand interactions, achieving state-of-the-art accuracy and interpretability. Trained on identical protein-ligand pairs without structural data, PSICHIC matched and even surpassed leading structure-based methods in binding affinity prediction. In a library screening for adenosine A1 receptor agonists, PSICHIC discerned functional effects effectively, ranking the sole novel agonist within the top three. PSICHIC’s interpretable fingerprints identified protein residues and ligand atoms involved in interactions. We foresee PSICHIC reshaping virtual screening and deepening our understanding of protein-ligand interactions."

# Summary. An optional shortened abstract.
summary: "**[Nature Machine Intelligence, 2024]** This paper introduces PSICHIC, a graph neural network framework that leverages physicochemical constraints to predict protein-ligand interactions directly from sequence data. PSICHIC achieves state-of-the-art accuracy in binding affinity prediction, even surpassing existing structure-based methods in certain cases. Furthermore, its interpretable fingerprints illuminate the specific protein residues and ligand atoms involved in these interactions, offering a promising tool for virtual screening and enhancing our understanding of protein-ligand mechanisms."

tags: [graph neural networks, drug discovery, AI for science]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://rdcu.be/dK2gY
url_code: https://github.com/huankoh/PSICHIC
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
