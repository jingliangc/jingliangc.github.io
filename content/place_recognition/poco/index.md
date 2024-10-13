---
title: 'PoCo: Point Context Cluster for RGBD Indoor Place Recognition'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Deng Zhuo
  - Zheming Zhou
  - Omid Ghasemalizadeh
  - Dinesh Manocha
  - Min Sun
  - Cheng-Hao Kuo
  - Arnie Sen

# Author notes (optional)
# author_notes:
#   - admin
#   - Utsav Patel
#   - Adarsh Jagan Sathyamoorthy
#   - Dinesh Manocha

date: '2024-10-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)
publication_short: In *IROS 2024*

abstract: We present a novel end-to-end algorithm (PoCo) for the indoor RGB-D place recognition task, aimed at identifying the most likely match for a given query frame within a reference database. The task presents inherent challenges attributed to the constrained field of view and limited range of perception sensors. We propose a new network architecture, which generalizes the recent Context of Clusters (CoCs) to extract global descriptors directly from the noisy point clouds through end-to-end learning. Moreover, we develop the architecture by integrating both color and geometric modalities into the point features to enhance the global descriptor representation. We conducted evaluations on public datasets ScanNet-PR and ARKit with 807 and 5047 scenarios, respectively. PoCo achieves SOTA performance on ScanNet-PR, we achieve R@1 of 64.63%, a 5.7% improvement from the best-published result CGis (61.12%); on Arkit, we achieve R@1 of 45.12%, a 13.3% improvement from the best-published result CGis (39.82%). In addition, PoCo shows higher efficiency than CGis in inference time (1.75X-faster), and we demonstrate the effectiveness of PoCo in recognizing places within a real-world laboratory environment.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - RGB-D Place Recognition
  - Indoor Place Recognition

# Display this page in the Featured widget?
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter
#- name: Conference Abstract
#  url:
#- name: Source Files
#  url: #https://archive.org
#  icon_pack: fas
#  icon: archive
#- name: Grant Proposal
#  url: #https://twitter.com
#  icon_pack: far
#  icon: file-alt
#- name: Blog Post
#  url: #https://twitter.com
#  icon_pack: far
#  icon: sticky-note
#- name: Review
#  url: #https://twitter.com
#  icon_pack: fas
#  icon: quote-left
#- name: Reddit
#  url: #https://twitter.com
#  icon_pack: fab
#  icon: reddit-alien
#- name: Publisher Page
#  url: #https://twitter.com
#  icon_pack: fas
#  icon: landmark
#- name: Amazon
#  url: #https://twitter.com
#  icon_pack: fab
#  icon: amazon
# Note there is an official Dataset theme item url_dataset
#- name: Data set
#  url: #https://twitter.com
#  icon_pack: fas
#  icon: dice-d20
#- name: Audio File
#  url: #http://hdl.handle.net/10125/25253
#  icon_pack: fas
#  icon: volume-off
#  icon: file-audio
#- name: Listen
#  url: "/talk/2015-contribution-of-women-to-linguistic-vitality-in-northwestern-nigeria//#listen"
#  icon_pack: fas
#  icon: headphones-alt
#- name: Archive Deposit
#  url:
#  icon_pack: fas
#  icon: landmark
#- name: Video File
#  url:
#  icon_pack: fas
#  icon: file-video
#- name: Watch
#  url: /talk/page/#watch
#  icon_pack: fas
#  icon: video
url_pdf: 'https://arxiv.org/pdf/2404.02885'
url_code: 'https://github.com/jingGM/PoCo-CCR'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/D8dObAeMiCw'

# links:
# - name: Website
#   url: 'https://www.ijcai.org/proceedings/2020/583'
#   icon_pack: fab
#   icon: twitter

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
 -->