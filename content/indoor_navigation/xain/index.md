---
title: 'XAI-N: Sensor-based robot navigation using expert policies and decision trees'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Aaron M Roth
  - admin
  - Dinesh Manocha

# Author notes (optional)
# author_notes:
#   - admin
#   - Utsav Patel
#   - Adarsh Jagan Sathyamoorthy
#   - Dinesh Manocha

date: '2021-09-27T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-09-27T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)
publication_short: In *IROS 2021*

abstract: We present a novel sensor-based learning navigation algorithm to compute a collision-free trajectory for a robot in dense and dynamic environments with moving obstacles or targets. Our approach uses deep reinforcement learning-based expert policy that is trained using a sim2real paradigm. In order to increase the reliability and handle the failure cases of the expert policy, we combine with a policy extraction technique to transform the resulting policy into a decision tree format. We use properties of decision trees to analyze and modify the policy and improve performance of navigation algorithm including smoothness, frequency of oscillation, frequency of immobilization, and obstruction of target. Overall, we are able to modify the policy to design an improved learning algorithm without retraining. We highlight the benefits of our approach in simulated environments and navigating a Clearpath Jackal robot among moving pedestrians. 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Interpretable Deep Learning
  - Decision tree
  - Indoor Navigation

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
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9636759'
url_code: 'https://github.com/AMR-/JackalCrowdEnv'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://gamma.umd.edu/researchdirections/xrl/navviper'

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