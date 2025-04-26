---
title: "TGS: Trajectory Generation and Selection using Vision Language Models in Mapless Outdoor Environments"
authors:
- Daeun Song
- admin
- Xuesu Xiao
- Dinesh Manocha

date: "2024-10-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We present a multi-modal trajectory generation and selection algorithm for real-world mapless outdoor navigation in challenging scenarios with unstructured off-road features like buildings, grass, and curbs. Our goal is to compute suitable trajectories that (1) satisfy the environment-specific traversability constraints and (2) match human-like paths while navigating in crosswalks, sidewalks, etc. Our formulation uses a Conditional Variational Autoencoder (CVAE) generative model enhanced with traversability constraints to generate multiple candidate trajectories for global navigation. We use VLMs and a visual prompting approach with their zero-shot ability of semantic understanding and logical reasoning to choose the best trajectory given the contextual information about the task. We evaluate our methods in various outdoor scenes with wheeled robots and compare the performance with other global navigation algorithms. In practice, we observe at least 3.35% improvement in the traversability and 20.61% improvement in terms of human-like navigation in generated trajectories in challenging outdoor navigation scenarios, such as sidewalks, crosswalks, etc.



# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Traversability Analysis
- Language Models
- Outdoor Navigation

featured: false

# links:
# - name: Website
#   url: https://robotixx.github.io/GND/
#   icon_pack: fab
#   icon: twitter
url_pdf: https://arxiv.org/pdf/2408.02454
url_code: 'https://github.com/GAMMA-UMD-Outdoor-Navigation/BehAV'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---