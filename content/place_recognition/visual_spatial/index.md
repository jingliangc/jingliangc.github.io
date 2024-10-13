---
title: 'Visual, Spatial, Geometric-Preserved Place Recognition for Cross-View and Cross-Modal Collaborative Perception'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Peng Gao
  - admin
  - Yu Shen
  - Sanghyun Son
  - Ming C. Lin

# Author notes (optional)
# author_notes:
#   - admin
#   - Utsav Patel
#   - Adarsh Jagan Sathyamoorthy
#   - Dinesh Manocha

date: '2022-10-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)
publication_short: In *IROS 2023*

abstract: Place recognition plays an important role in multirobot collaborative perception, such as aerial-ground search and rescue, in order to identify the same place they have visited. Recently, approaches based on semantics showed the promising performance to address cross-view and cross-modal challenges in place recognition, which can be further categorized as graphbased and geometric-based methods. However, both methods have shortcomings, including ignoring geometric cues and affecting by large non-overlapped regions between observations. In this paper, we introduce a novel approach that integrates semantic graph matching and distance fields (DF) matching for cross-view and cross-modal place recognition. Our method uses a graph representation to encode visual-spatial cues of semantics and uses a set of class-wise DFs to encode geometric cues of a scene. Then, we formulate place recognition as a two-step matching problem. We first perform semantic graph matching to identify the correspondence of semantic objects. Then, we estimate the overlapped regions based on the identified correspondences and further align these regions to compute their geometricbased DF similarity. Finally, we integrate graph-based similarity and geometry-based DF similarity to match places. We evaluate our approach over two public benchmark datasets, including KITTI and AirSim. Compared with the previous methods, our approach achieves around 10% improvement in ground-ground place recognition in KITTI and 35% improvement in aerialground place recognition in AirSim.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Multiple Modality
  - Place Recognition

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
url_pdf: 'https://www.cs.umd.edu/~yushen/docs/IROS2023.pdf'
url_code: ''
url_dataset: ''
url_poster: 'https://robotics.umd.edu/news/story/umd-team-wins-ieee-iros-best-paper-award-in-agrirobotics'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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