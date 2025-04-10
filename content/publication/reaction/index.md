---
title: 'Safe Collision and Clamping Reaction for Parallel Robots During Human-Robot Collaboration'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Moritz Schappler
  - Tim-Lukas Habich
  - Tobias Ortmaier

 # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-10-01T00:00:01Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 International Conference on Intelligent Robots and Systems*

abstract: Parallel robots (PRs) offer the potential for safe human-robot collaboration because of their low moving masses. Due to the in-parallel kinematic chains, the risk of contact in the form of collisions and clamping at a chain increases. Ensuring safety is investigated in this work through various contact reactions on a real planar PR. External forces are estimated based on proprioceptive information and a dynamics model, which allows contact detection. Retraction along the direction of the estimated line of action provides an instantaneous response to limit the occurring contact forces within the experiment to 70 N at a maximum velocity of 0.4 m/s. A reduction in the stiffness of a Cartesian impedance control is investigated as a further strategy. For clamping, a feedforward neural network (FNN) is trained and tested in different joint angle configurations to classify whether a collision or clamping occurs with an accuracy of 80{\%}. A second FNN classifies the clamping kinematic chain to enable a subsequent kinematic projection of the clamping joint angle onto the rotational platform coordinates. In this way, a structure opening is performed in addition to the softer retraction movement. The reaction strategies are compared in real-world experiments at different velocities and controller stiffnesses to demonstrate their effectiveness. The results show that in all collision and clamping experiments the PR terminates the contact in less than 130 ms.

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

url_pdf: 'https://arxiv.org/abs/2308.09656'
url_code: 'https://aranmoha.github.io/SafePR/20_planar_parallel_robot/#structure'
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

<iframe width="645" height="362" src="https://youtube.com/embed/pcIBYYhcWk4?si=jempzsBbnGImf_7Z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<p style="margin-top: 0.5rem; font-size: 0.95rem; color: #555;">
  Video: Published results on reactive safety strategy for collision and clamping contacts
</p>

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
