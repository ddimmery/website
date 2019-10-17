+++
title = "Permutation Weighting"
date = 2019-01-08T22:51:39-05:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["David Arbour", "Drew Dimmery"]

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
abstract = """
This work introduces permutation weighting: a weighting estimator for observational causal inference under general treatment regimes which preserves arbitrary measures of covariate balance. We show that estimating weights which obey balance constraints is equivalent to a simple binary classification problem between the observed data and a permuted dataset (no matter the cardinality of treatment). Arbitrary probabilistic classifiers may be used in this method; the hypothesis space of the classifier corresponds to the nature of the balance constraints imposed through the resulting weights.We show equivalence between existing covariate balancing weight estimators and permutation weighting and demonstrate estimation with improved efficiency through this regime. We provide theoretical results on the consistency of estimation of causal effects, and the necessity of balance infinite samples. Empirical evaluations indicate that the proposed method outperforms existing state of the art weighting methods for causal effect estimation, even when the data generating process corresponds to the assumptions imposed by prior work.
"""
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
url_pdf = "https://arxiv.org/pdf/1901.01230.pdf"
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
