+++
title = "Experiment Shrinkage"
date = 2017-10-28
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Drew Dimmery", "Jasjeet Sekhon", "Eytan Bakshy"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "Conference on Digital Experimentation, 2017"
publication_short = "CODE 2017"

# Abstract and optional shortened version.
abstract = "We develop and analyze Empirical Bayes Stein-type estimators for use in the estimation of causal effects in large-scale online experiments. While online experiments are generally thought to be distinguished by their large sample size, they also tend to have both a high cardinality of treatment groups and of outcome measures. Even in this high-dimensional setting, though, the typical analysis practice is to use simple differences-in-means (perhaps with covariate adjustment) as if all treatment arms and outcomes were independent. We show that this approach is inadmissable. We develop shrinkage estimators which are trivially consistent (albeit with small amounts of bias in small samples). In addition to achieving lower mean squared error these estimators retain important frequentist properties such as coverage under most reasonable scenarios. Modern methods of experimentation such as multi-armed bandit optimization (where treatment allocations adapt over time to prior responses) also benefit from the use of our shrinkage estimators. We demonstrate the usefulness of these methods by examining seventeen large-scale experiments conducted on Facebook from April to June 2017."
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
