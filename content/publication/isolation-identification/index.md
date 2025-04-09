---
title: 'Collision Isolation and Identification Using Proprioceptive Sensing for Parallel Robots to Enable Human-Robot Collaboration'

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

date: '2023-10-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 International Conference on Intelligent Robots and Systems*

abstract: Parallel robots (PRs) allow for higher speeds in human-robot collaboration due to their lower moving masses but are more prone to unintended contact. For a safe reaction, knowledge of the location and force of a collision is useful. A novel algorithm for collision isolation and identification with proprioceptive information for a real PR is the scope of this work. To classify the collided body, the effects of contact forces at the links and platform of the PR are analyzed using a kinetostatic projection. This insight enables the derivation of features from the line of action of the estimated external force. The significance of these features is confirmed in experiments for various load cases. A feedforward neural network (FNN) classifies the collided body based on these physically modeled features. Generalization with the FNN to 300k load cases on the whole robot structure in other joint angle configurations is successfully performed with a collision-body classification accuracy of 84% in the experiments. Platform collisions are isolated and identified with an explicit solution, while a particle filter estimates the location and force of a contact on a kinematic chain. Updating the particle filter with estimated external joint torques leads to an isolation error of less than 3cm and an identification error of 4N in a real-world experiment.

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

url_pdf: 'https://arxiv.org/abs/2308.09650'
url_code: 'https://aranmoha.github.io/SafePR/20_planar_parallel_robot/#structure'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://youtu.be/xD6Zaj6p1f8?si=buRTt7Sk4SaDFj5j'

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
