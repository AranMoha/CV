---
title: 'Towards Human-Robot Collaboration with Parallel Robots by Kinetostatic Analysis, Impedance Control and Contact Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Moritz Schappler
  - Tobias Ortmaier

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-05-29T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 International Conference on Robotics and Automation*

abstract: Parallel robots provide the potential to be lever-aged for human-robot collaboration (HRC) due to low collision energies even at high speeds resulting from their reduced moving masses. However, the risk of unintended contact with the leg chains increases compared to the structure of serial robots. As a first step towards HRC, contact cases on the whole parallel robot structure are investigated and a disturbance observer based on generalized momenta and measurements of motor current is applied. In addition, a Kalman filter and a second-order sliding-mode observer based on generalized momenta are compared in terms of error and detection time. Gearless direct drives with low friction improve external force estimation and enable low impedance. The experimental validation is performed with two force-torque sensors and a kinetostatic model. This allows a new identification method of the motor torque constant of an assembled parallel robot to estimate external forces from the motor current and via a dynamics model. A Cartesian impedance control scheme for compliant robot-environmental dynamics with stiffness from 0.1-2N/mm and the force observation for low forces over the entire structure are validated. The observers are used for collisions and clamping at velocities of 0.4-0.9 m/s for detection within 9–58 ms and a reaction in the form of a zero-g mode.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
#   - Large Language Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2308.09633'
url_code: 'https://aranmoha.github.io/SafePR/20_planar_parallel_robot/#structure'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtu.be/HaazrQsKVhY?feature=shared'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<iframe width="645" height="362" src="https://youtube.com/embed/HaazrQsKVhY?si=8DpXQBM71zcANZ1v" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<p style="margin-top: 0.5rem; font-size: 0.95rem; color: #555;">
  Video: Published results on force estimation, interaction control and contact detection
</p>

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
