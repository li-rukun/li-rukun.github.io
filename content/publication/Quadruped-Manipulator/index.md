---
title: 'Stable Locomotion Control for Quadruped Mobile Manipulator Based on Adaptive Estimation of Load Mass'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Rukun Li
  - Baoshuo Feng
  - Zixin Hao
  - Lixia Liu
  - Yaxian Xin
  - Bin Li

# Author notes (optional)
author_notes:
  - 'Main contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

# date: '2024-05-25T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-27T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *China Intelligent Systems Conference*
publication_short: In *CISC*

abstract: The motion and operation of quadruped robots integrated with a manipulator are significant challenges in the field of legged robotics. In this paper, a stable locomotion control method for the quadruped mobile manipulator based on adaptive estimation of load mass is proposed. Firstly, the motion in the joint space is mapped to the end of the manipulator to obtain the motion state of the load, and the load mass is estimated based on the torso dynamics properties. Then, the force required to maintain the motion of the load and manipulator is obtained based on the manipulator dynamics model. Finally, by extending the torso dynamics model, this generalized force is used as a feed-forward compensation term in the upper controller planning to obtain the leg joint torques that satisfy both the torso motion demand and the force required by the manipulator. The feasibility and validity of the proposed method are verified based on the simulation software of Webots. Simulation results show that the robot can estimate the quality of the load and overcome the effects caused by the load to keep itself stable, which can improve the operating performance of the quadruped mobile manipulator.

# Summary. An optional shortened abstract.
summary: The motion and operation of quadruped robots integrated with a manipulator are significant challenges in the field of legged robotics. In this paper, a stable locomotion control method for the quadruped mobile manipulator based on adaptive estimation of load mass is proposed. Firstly, the motion in the joint space is mapped to the end of the manipulator to obtain the motion state of the load, and the load mass is estimated based on the torso dynamics properties. Then, the force required to maintain the motion of the load and manipulator is obtained based on the manipulator dynamics model. Finally, by extending the torso dynamics model, this generalized force is used as a feed-forward compensation term in the upper controller planning to obtain the leg joint torques that satisfy both the torso motion demand and the force required by the manipulator. The feasibility and validity of the proposed method are verified based on the simulation software of Webots. Simulation results show that the robot can estimate the quality of the load and overcome the effects caused by the load to keep itself stable, which can improve the operating performance of the quadruped mobile manipulator.

tags:
  - Quadruped robot
  - Manipulator
  - Virtual model control
  - Adaptive estimation

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

<!-- [Full text link](https://ieeexplore.ieee.org/document/10587825) -->
