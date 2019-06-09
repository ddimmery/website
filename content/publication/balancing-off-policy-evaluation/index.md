+++
title = "Balanced Off-Policy Evaluation in General Action Spaces"
date = 2019-06-09
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Arjun Sondhi", "David Arbour", "Drew Dimmery"]

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
abstract = "In many practical applications of contextual bandits, online learning is infeasible and practitioners must rely on off-policy evaluation (OPE) of logged data collected from prior policies. OPE generally consists of a combination of two components: (i) directly estimating a model of the reward given state and action and (ii) importance sampling. While recent work has made significant advances adaptively combining these two components, less attention has been paid to improving the quality of the importance weights themselves. In this work we present balancing off-policy evaluation (BOP-e), an importance sampling procedure that directly optimizes for balance and can be plugged into any OPE estimator that uses importance sampling. BOP-e directly estimates the importance sampling ratio via a classifier which attempts to distinguish state-action pairs from an observed versus a proposed policy. BOP-e can be applied to continuous, mixed, and multi-valued action spaces without modification and is easily scalable to many observations. Further, we show that minimization of regret in the constructed binary classification problem translates directly into minimizing regret in the off-policy evaluation task. Finally, we provide experimental evidence that BOP-e outperforms inverse propensity weighting-based approaches for offline evaluation of policies in the contextual bandit setting under both discrete and continuous action spaces."
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
