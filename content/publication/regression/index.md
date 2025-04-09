---
title: 'Hybrid Physical and Machine Learning-Oriented Modeling Approach to Predict Emissions in a Diesel Compression Ignition'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Reza Rezaei
  - Christopher Hayduk
  - Thaddaeus O. Delebinski
  - Saeid Shahpouri
  - Mahdi Shahbakhti

 # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-04-06T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-08T00:00:01Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2021 SAE Technical Paper Series*

abstract: The development and calibration of modern combustion engines is challenging in the area of continuously tightening emission limits and the necessity for meeting real driving emissions regulations. A focus is on the knowledge of the internal engine processes and the determination of pollutants formations in order to predict the engine emissions. A physical model-based development provides an insight into hardly measurable phenomena properties and is robust against changing input data. With increasing modeling depth the required computing capacities increase. As an alternative to physical modeling, data-driven machine learning methods can be used to enable high-performance modeling accuracy. However, these are dependent on the learned data. To combine the performance and robustness of both types of modeling a hybrid application of data-driven and physical models is developed in this paper as a grey box model for the exhaust emission prediction of a commercial vehicle diesel engine. Internal engine processes are physically investigated to determine combustion characteristic quantities influencing the formation of NOx, CO, HC and soot emissions. With the physically modeled inputs, models based on machine learning methods, including Support Vector Machine and Feedforward Neural Network, are developed for emission modeling. The models are trained using the data from a commercial vehicle engine, validated against different hyperparameters and network architectures and tested against each other at 772 different operating points. A comparison is made to black box models formed from the measured data. In general, feedforward neural networks and support vector machines were enhanced by selecting the physically modeled inputs. The feedforward neural networks for HC and soot modeling were improved by approximately 20% and 10% with respect to the RMSE of the test data. For the support vector machines, CO and soot modeling benefited the most by 30% and 20% respectively of the RMSE of the test data. For a trained NOx model based on low load data its coefficient of determination regarding test data by high load is increased from 0.807 to 0.908.

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

url_pdf: 'https://www.sae.org/publications/technical-papers/content/2021-01-0496/'
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
