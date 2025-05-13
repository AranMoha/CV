---
title: 'Fast Contact Detection via Fusion of Joint and Inertial Sensors for Parallel Robots in Human-Robot Collaboration'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jan Piosik
  - Dustin Lehmann
  - Thomas Seel
  - Moritz Schappler

 # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-05-10T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-05-13T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *2025 IEEE Robotics and Automation Letters*

abstract: Fast contact detection is crucial for safe human-robot collaboration. Observers based on proprioceptive information can be used for contact detection but have first-order error dynamics, which results in delays. Sensor fusion based on inertial measurement units (IMUs) consisting of accelerometers and gyroscopes is advantageous for reducing delays. The acceleration estimation enables the direct calculation of external forces. For serial robots, the installation of multiple accelerometers and gyroscopes is required for dynamics modeling since the joint coordinates are the minimal coordinates. Alternatively, parallel robots (PRs) offer the potential to use only one IMU on the end-effector platform, which already presents the minimal coordinates of the PR. This work introduces a sensor-fusion method for contact detection using encoders and only one low-cost, consumer-grade IMU for a PR. The end-effector accelerations are estimated by an extended Kalman filter and incorporated into the dynamics to calculate external forces. In real-world experiments with a planar PR, we demonstrate that this approach reduces the detection duration by up to 50% compared to a momentum observer and enables the collision and clamping detection within 3-39ms.

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

# url_pdf: 'https://arxiv.org/abs/2408.15831'
# url_code: 'https://aranmoha.github.io/SafePR/20_planar_parallel_robot/#structure'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtu.be/pcIBYYhcWk4?feature=shared'

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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
