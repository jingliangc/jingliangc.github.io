---
title: "Social-LLaVA: Enhancing Robot Navigation through Human-Language Reasoning in Social Spaces"
authors:
- Amirreza Payandeh
- Daeun Song
- Mohammad Nazeri
- admin
- Praneel Mukherjee
- Amir Hossain Raj
- Yangzhe Kong
- Dinesh Manocha
- Xuesu Xiao

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

abstract: Most existing social robot navigation techniques either leverage hand-crafted rules or human demonstrations to connect robot perception to socially compliant actions. However, there remains a significant gap in effectively translating perception into socially compliant actions, much like how human reasoning naturally occurs in dynamic environments. Considering the recent success of Vision-Language Models (VLMs), we propose using language to bridge the gap in human-like reasoning between perception and socially aware robot actions. We create a vision-language dataset, Social robot Navigation via Explainable Interactions (SNEI), featuring 40K human-annotated Visual Question Answers (VQAs) based on 2K human-robot social interactions in unstructured, crowded public spaces, spanning perception, prediction, chainof-thought reasoning, action, and explanation. We fine-tune a VLM, Social-LLaVA, using SNEI to demonstrate the practical application of our dataset. Social-LLaVA outperforms state-ofthe-art models like GPT-4V and Gemini, based on the average of fifteen different human-judge scores across 50 VQAs. Deployed onboard a mobile robot, Social-LLaVA enables human-like reasoning, marking a promising step toward socially compliant robot navigation in dynamic public spaces through language reasoning.



# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Social Navigation
- Language Models
- Outdoor Navigation

featured: true

# links:
# - name: Website
#   url: https://robotixx.github.io/GND/
#   icon_pack: fab
#   icon: twitter
url_pdf: https://arxiv.org/pdf/2501.09024
url_code: ""
url_dataset: ''
url_poster: ''
url_project: 'https://cs.gmu.edu/~xiao/Research/SNEI/'
url_slides: ''
url_source: ''
url_video: ""

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