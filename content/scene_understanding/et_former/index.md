---
title: "ET-Former: Efficient Triplane Deformable Attention for 3D Semantic Scene Completion From Monocular Camera"
authors:
- admin
- He Yin
- Xuewei Qi
- Jong Jin Park
- Min Sun
- Rajasimman Madhivanan
- Dinesh Manocha

date: "2025-06-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)
publication_short: In *IROS 2025*

abstract: "We introduce ET-Former, a novel end-to-end algorithm for semantic scene completion using a single monocular camera. Our approach generates a semantic occupancy map from single RGB observation while simultaneously providing uncertainty estimates for semantic predictions. By designing a triplane-based deformable attention mechanism, our approach improves geometric understanding of the scene than other SOTA approaches and reduces noise in semantic predictions. Additionally, through the use of a Conditional Variational AutoEncoder (CVAE), we estimate the uncertainties of these predictions. The generated semantic and uncertainty maps will aid in the formulation of navigation strategies that facilitate safe and permissible decision-making in the future. Evaluated on the Semantic-KITTI dataset, ET-Former achieves the highest IoU and mIoU, surpassing other methods by 15.16% in IoU and 24.24% in mIoU, while reducing GPU memory usage of existing methods by 25%-50.5%."


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Semantic Scene Completion
- Scene Understanding
- Autonomous Driving

featured: true

# links:
# - name: Website
#   url: https://robotixx.github.io/GND/
#   icon_pack: fab
#   icon: twitter
url_pdf: "https://arxiv.org/pdf/2410.11019"
url_code: 'https://github.com/jingGM/ET-Former.git'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/2c06AKUAXys'

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