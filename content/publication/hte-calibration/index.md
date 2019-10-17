+++
title = "Calibration of Heterogeneous Treatment Effects"
date = 2019-10-16T20:17:47-04:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Yan Leng", "Drew Dimmery"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = ""
publication_short = ""

# Abstract and optional shortened version.
abstract = "Using machine learning to estimate the heterogeneity of treatment effects (HTE) in randomized experiments is a common practice when seeking to understand how units differ in their response to a treatment. These HTE models are often used by Web platforms to construct personalized policies (for instance, by enabling a feature only for those users who are estimated to have a positive treatment effect). Unfortunately, many HTE models have no guarantees on the calibration of subgroup effects: that effect estimates of a particular size will, on average, be that size. We provide a simple way to calibrate black-box estimates of HTEs to known unbiased average effect estimates, ensuring that sign and magnitude will approximate experimental benchmarks. Our method is broadly in the vein of the popular Platt (1999) technique used in supervised learning. It requires no additional data beyond that necessary for estimating HTEs, and it can be trivially scaled to arbitrarily large datasets. Our technique enables the use of stacking to ensemble estimates from multiple HTE models based on their out-of-sample estimates, allowing for better performance than the constituent models in the ensemble. Simulation evidence shows that our method is effective at improving HTE estimates. We show that this matters in the real-world by applying our method to an experiment run at Facebook."
abstract_short = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
