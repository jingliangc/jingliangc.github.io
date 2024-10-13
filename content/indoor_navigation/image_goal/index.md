---
title: 'Image-goal navigation in complex environments via modular learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Qiaoyun Wu
  - Jun Wang
  - admin
  - Xiaoxi Gong
  - Dinesh Manocha

# Author notes (optional)
# author_notes:
#   - admin
#   - Utsav Patel
#   - Adarsh Jagan Sathyamoorthy
#   - Dinesh Manocha

date: '2022-05-30T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: 2022 IEEE Robotics and Automation Letters
publication_short: In *RA-L 2022*

abstract: We present a novel approach for image-goal navigation, where an agent navigates with a goal image rather than accurate target information, which is more challenging. Our goal is to decouple the learning of navigation goal planning, collision avoidance, and navigation ending prediction, which enables more concentrated learning of each part. This is realized by four different modules. The first module maintains an obstacle map during robot navigation. The second predicts a long-term goal on the real-time map periodically, which can thus convert an image-goal navigation task to several point-goal navigation tasks. To achieve these point-goal navigation tasks, the third module plans collision-free command sets for navigating to these long-term goals. The final module stops the robot properly near the goal image. The four modules are designed or maintained separately, which helps cut down the search time during navigation and improve the generalization to previously unseen real scenes. We evaluate the method in both a simulator and in the real world with a mobile robot. The results in real complex environments show that our method attains at least a 17% increase in navigation success rate and a 23% decrease in navigation collision rate over some state-of-the-art models.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Image Goal
  - Indoor Navigation

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
url_pdf: 'https://arxiv.org/pdf/2108.06105'
url_code: ''
url_dataset: ''
url_poster: ''
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