---
title: 'Adaptiveon: Adaptive outdoor local navigation method for stable and reliable actions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Kasun Weerakoon
  - Tianrui Guan
  - Nare Karapetyan
  - Dinesh Manocha

# Author notes (optional)
# author_notes:
#   - admin
#   - Utsav Patel
#   - Adarsh Jagan Sathyamoorthy
#   - Dinesh Manocha

date: '2022-12-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-12-16T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal'] # ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: IEEE Robotics and Automation Letters 2022
publication_short: In *RA-L 2022*

abstract: We present a novel outdoor navigation algorithm to generate stable and efficient actions to navigate a robot to reach a goal. We use a multi-stage training pipeline and show that our approach produces policies that result in stable and reliable robot navigation on complex terrains. Based on the Proximal Policy Optimization (PPO) algorithm, we developed a novel method to achieve multiple capabilities for outdoor navigation tasks, namely alleviating the robot's drifting, keeping the robot stable on bumpy terrains, avoiding climbing on hills with steep elevation changes, and avoiding collisions. Our training process mitigates the reality (sim-to-real) gap by introducing generalized environmental and robotic parameters and training with rich features of Lidar perception in a high-fidelity Unity simulator. We evaluate our method in both simulation and real world environments using Clearpath Husky and Jackal robots. Further, we compare our method against the state-of-the-art approaches and observe that, in the real world it improves stability by at least 30.7% on uneven terrains, reduces drifting by 8.08% and decreases the elevation changes by 14.75%.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Traversability Analasis
  - Outdoor Navigation
  - Reinforcement Learning

# Display this page in the Featured widget?
featured: false

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
url_pdf: 'https://arxiv.org/pdf/2205.03517'
url_code: 'https://github.com/jingGM/adaptiveON'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/x4N_vHrmIeA'

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