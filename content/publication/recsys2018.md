+++
title = "The Art of Drafting: A Team-Oriented Hero Recommendation System for Multiplayer Online Battle Arena Games"
date = 2018-07-10T14:56:23-04:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Zhengxing Chen", "Truong-Huy D. Nguyen", "Yuyu Xu",
			"Chris Amato", "Seth Cooper", "Yizhou Sun", "Magy Seif El-Nasr"]

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
publication = "ACM Conference on Recommender Systems"
publication_short = "RecSys"

# Abstract and optional shortened version.
abstract = "Multiplayer Online Battle Arena (MOBA) games have received increasing popularity recently. In a match of such games, players compete in two teams of five, each controlling an in-game avatars, known as heroes, selected from a roster of more than 100. The selection of heroes, also known as pick or draft, takes place before the match starts and alternates between the two teams until each player has selected one hero. Heroes are designed with different strengths and weaknesses to promote team cooperation in a game. Intuitively, heroes in a strong team should complement each other's strengths and suppressing those of opponents. Hero drafting is therefore a challenging problem due to the complex hero-to-hero relationships to consider. In this paper, we propose a novel hero recommendation system that suggests heroes to add to an existing team while maximizing the team's prospect for victory. To that end, we model the drafting between two teams as a combinatorial game and use Monte Carlo Tree Search (MCTS) for estimating the values of hero combinations. Our empirical evaluation shows that hero teams drafted by our recommendation algorithm have significantly higher win rate against teams constructed by other baseline and state-of-the-art strategies."
abstract_short = "Hero recommendation is formulated as a sequential decision making problem and solved using Monte Carlo Tree Search (UCT)."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = ["behavior_analytics"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["mcts", "mdp", "moba", "recommendation"]

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/pdf/1806.10130"
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
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
