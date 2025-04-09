---
title: 'Physical-oriented and machine learning-based emission modeling in a diesel compression ignition engine: Dimensionality reduction and regression'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Aran Mohammad
  - Reza Rezaei
  - Christopher Hayduk
  - Thaddaeus Delebinski
  - Saeid Shahpouri
  - Mahdi Shahbakhti


 # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-01-06T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *2022 International Journal of Engine Research*

abstract: The development of internal combustion engines is affected by the exhaust gas emissions legislation and the striving to increase performance. This demands for engine-out emission models that can be used for engine optimization for real driving emission controls. The prediction capability of physically and data-driven engine-out emission models is influenced by the system inputs, which are specified by the user and can lead to an improved accuracy with increasing number of inputs. Thereby the occurrence of irrelevant inputs becomes more probable, which have a low functional relation to the emissions and can lead to overfitting. Alternatively, data-driven methods can be used to detect irrelevant and redundant inputs. In this work, thermodynamic states are modeled based on 772 stationary measured test bench data from a commercial vehicle diesel engine. Afterward, 37 measured and modeled variables are led into a data-driven dimensionality reduction. For this purpose, approaches of supervised learning, such as lasso regression and linear support vector machine, and unsupervised learning methods like principal component analysis and factor analysis are applied to select and extract the relevant features. The selected and extracted features are used for regression by the support vector machine and the feedforward neural network to model the NOx, CO, HC, and soot emissions. This enables an evaluation of the modeling accuracy as a result of the dimensionality reduction. Using the methods in this work, the 37 variables are reduced to 25, 22, 11, and 16 inputs for NOx, CO, HC, and soot emission modeling while maintaining the accuracy. The features selected using the lasso algorithm provide more accurate learning of the regression models than the extracted features through principal component analysis and factor analysis. This results in test errors RMSETe for modeling NOx, CO, HC, and soot emissions 19.22 ppm, 6.46 ppm, 1.29 ppm, and 0.06 FSN, respectively.

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

url_pdf: 'https://journals.sagepub.com/doi/full/10.1177/14680874211070736'
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
