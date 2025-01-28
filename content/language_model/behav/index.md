---
title: "BehAV: Behavioral Rule Guided Autonomy Using VLMs for Robot Navigation in Outdoor Scenes"
authors:
- Kasun Weerakoon
- Mohamed Elnoor
- Gershom Seneviratne
- Vignesh Rajagopal
- Senthil Hariharan Arul
- admin
- Mohamed Khalid M Jaffar
- Dinesh Manocha

date: "2025-01-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-26T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Robotics and Automation (ICRA), 2025"
publication_short: In *ICRA 2025*

abstract: We present BehAV, a novel approach for autonomous robot navigation in outdoor scenes guided by human instructions and leveraging Vision Language Models (VLMs). Our method interprets human commands using a Large Language Model (LLM), and categorizes the instructions into navigation and behavioral guidelines. Navigation guidelines consist of directional commands (e.g., "move forward until") and associated landmarks (e.g., "the building with blue windows"), while behavioral guidelines encompass regulatory actions (e.g., "stay on") and their corresponding objects (e.g., "pavements"). We use VLMs for their zero-shot scene understanding capabilities to estimate landmark locations from RGB images for robot navigation. Further, we introduce a novel scene representation that utilizes VLMs to ground behavioral rules into a behavioral cost map. This cost map encodes the presence of behavioral objects within the scene and assigns costs based on their regulatory actions. The behavioral cost map is integrated with a LiDAR-based occupancy map for navigation. To navigate outdoor scenes while adhering to the instructed behaviors, we present an unconstrained Model Predictive Control (MPC)-based planner that prioritizes both reaching landmarks and following behavioral guidelines. We evaluate the performance of BehAV on a quadruped robot across diverse real-world scenarios, demonstrating a 22.49% improvement in alignment with human-teleoperated actions, as measured by Fréchet distance, and achieving a 40% higher navigation success rate compared to state-of-the-art methods.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Traversability Analysis
- Language Models
- Outdoor Navigation

featured: true

# links:
# - name: Website
#   url: https://robotixx.github.io/GND/
#   icon_pack: fab
#   icon: twitter
url_pdf: https://arxiv.org/pdf/2409.16484
url_code: 'https://github.com/GAMMA-UMD-Outdoor-Navigation/BehAV'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/oJV8b86k5rE'

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