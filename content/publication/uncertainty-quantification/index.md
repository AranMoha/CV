---
title: 'Quantifying Uncertainties of Contact Classifications in a Human-Robot Collaboration with Parallel Robots'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Hendrik Muscheid
  - Moritz Schappler
  - Thomas Seel

 # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-09-20T00:00:01Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 International Workshop on Human-Friendly Robotics*

abstract: In human-robot collaboration, unintentional physical contacts occur in the form of collisions and clamping, which must be detected and classified separately for a reaction. If certain collision or clamping situations are misclassified, reactions might occur that make the true contact case more dangerous. This work analyzes data-driven modeling based on physically modeled features like estimated external forces for clamping and collision classification with a real parallel robot. The prediction reliability of a feedforward neural network is investigated. Quantification of the classification uncertainty enables the distinction between safe versus unreliable classifications and optimal reactions like a retraction movement for collisions, structure opening for the clamping joint, and a fallback reaction in the form of a zero-g mode. This hypothesis is tested with experimental data of clamping and collision cases by analyzing dangerous misclassifications and then reducing them by the proposed uncertainty quantification. Finally, it is investigated how the approach of this work influences correctly classified clamping and collision scenarios.

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

url_pdf: 'https://arxiv.org/abs/2308.09675'
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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
