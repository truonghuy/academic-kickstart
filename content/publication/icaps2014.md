+++
title = "Bootstrapping Simulation-Based Algorithms with a Suboptimal Policy"
date = 2014-10-25T23:15:47-04:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Truong-Huy Dinh Nguyen", "Tomi Silander", "Wee-Sun Lee", "Tze-Yun Leong"]

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
publication = "International Conference on Automated Planning and Scheduling"
publication_short = "ICAPS"

# Abstract and optional shortened version.
abstract = "Finding optimal policies for Markov Decision Processes with large state spaces is in general intractable. Nonetheless, simulation-based algorithms inspired by Sparse Sampling (SS) such as Upper Confidence Bound applied in Trees (UCT) and Forward Search Sparse Sampling (FSSS) have been shown to perform reasonably well in both theory and practice, despite the high computational demand. To improve the efficiency of these algorithms, we adopt a simple enhancement technique with a heuristic policy to speed up the selection of optimal actions. The general method, called Aux, augments the look-ahead tree with auxiliary arms that are evaluated by the heuristic policy. In this paper, we provide theoretical justification for the method and demonstrate its effectiveness in two experimental benchmarks that showcase the faster convergence to a near optimal policy for both SS and FSSS. Moreover, to further speed up the convergence of these algorithms at the early stage, we present a novel mechanism to combine them with UCT so that the resulting hybrid algorithm is superior to both of its components."
abstract_short = "The Aux technique, introduced in the ECML/PKDD 2012 paper, is extended to other sampling-based algorithms such as Sparse Sampling and FSSS, with theoretical guarantee. Numerical evaluations demonstrate the utility of the proposed technique."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["mdp", "markov decision process", "sparse sampling", "forward sparse sampling", "heuristic"]

# Links (optional).
url_pdf = "http://www.aaai.org/ocs/index.php/ICAPS/ICAPS14/paper/viewFile/7934/8027"
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

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
