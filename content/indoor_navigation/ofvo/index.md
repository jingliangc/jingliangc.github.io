---
title: 'OF-VO: Efficient Navigation Among Pedestrians Using Commodity Sensors'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yi-Ling Qiao
  - Tianrui Guan
  - Dinesh Manocha

# Author notes (optional)
# author_notes:
#   - admin
#   - Utsav Patel
#   - Adarsh Jagan Sathyamoorthy
#   - Dinesh Manocha

date: '2021-06-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-06-18T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: IEEE Robotics and Automation Letters 2021
publication_short: In *RA-L 2021*

abstract: We present a novel high fidelity 3-D simulator that significantly reduces the sim-to-real gap for collision avoidance in dense crowds using Deep Reinforcement Learning (DRL). Our simulator models realistic crowd and pedestrian behaviors, along with friction, sensor noise and delays in the simulated robot model. We also describe a technique to incrementally control the randomness and complexity of training scenarios to achieve better convergence and generalization capabilities. We demonstrate the effectiveness of our simulator by training a policy that fuses data from multiple perception sensors such as a 2-D lidar and a depth camera to detect pedestrians and computes smooth, collision-free velocities. Our novel reward function and multi-sensor formulation results in smooth and unobtrusive navigation. We have evaluated the learned policy on two differential drive robots and evaluate its performance in new dense crowd scenarios, narrow corridors, T and L-junctions, etc. We observe that our algorithm outperforms prior dynamic navigation techniques in terms of metrics such as success rate, trajectory length, mean time to goal, and smoothness.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Indoor Collision Avoidance
  - Indoor Navigation

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2004.10976'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/BR4_CXs1QbU'

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