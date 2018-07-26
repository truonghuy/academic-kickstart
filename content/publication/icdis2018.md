+++
title = "Hand Gesture Controlled Drones: An Open Source Library"
date = 2018-04-10T15:21:15-04:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Kathiravan Natarajan", "Truong-Huy D. Nguyen", "Mutlu Mete"]

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
publication = "International Conference on Data Intelligence and Security"
publication_short = "ICDIS"

# Abstract and optional shortened version.
abstract = "Drones are conventionally controlled using joysticks, remote controllers, mobile applications, and embedded computers. A few significant issues with these approaches are that drone control is limited by the range of electromagnetic radiation and susceptible to interference noise. In this study we propose the use of hand gestures as a method to control drones. We investigate the use of computer vision methods to develop an intuitive way of agent-less communication between a drone and its operator. Computer vision-based methods rely on the ability of a drone's camera to capture surrounding images and use pattern recognition to translate images to meaningful and/or actionable information. The proposed framework involves a few key parts toward an ultimate action to be taken. They are: image segregation from the video streams of front camera, creating a robust and reliable image recognition based on segregated images, and finally conversion of classified gestures into actionable drone movement, such as takeoff, landing, hovering and so forth. A set of five gestures are studied in this work. Haar feature-based AdaBoost classifier[1] is employed for gesture recognition. We also envisage safety of the operator and drone's action calculating the distance based on computer vision for this task. A series of experiments are conducted to measure gesture recognition accuracies considering the major scene variabilities, illumination, background, and distance. Classification accuracies show that well-lit, clear background, and within 3 ft gestures are recognized correctly over 90%. Limitations of current framework and feasible solutions for better gesture recognition are discussed, too. The software library we developed, and hand gesture datasets are open-sourced at project website."
abstract_short = "There is some potential in controlling drones using hand gestures, as demonstrated by our preliminary study. Lighting, background visuals, and lighting remain as factors negatively affecting the performance."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = ["social_robotics"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["gesture control", "drone"]

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/abstract/document/8367759/"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = "https://github.com/KathiravanNatarajan/HandGestureControlledDrones"
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
