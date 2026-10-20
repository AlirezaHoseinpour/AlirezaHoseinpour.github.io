---
title: "Yggdrasil: A Layer-First 3D Scene Graph for Real-Time Querying"
authors:
- Arshia Akhavan
- Ermanno Bartoli
- Afnan Algharbi
- admin
- Iolanda Leite
- Bryan Donyanavard
date: "2026-09-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint arXiv:2609.38640"
publication_short: "arXiv"

abstract: |-
  Robotic agents use 3D scene graphs (3DSG) to perform tasks ranging from scene understanding to scene interaction. Although an extensive body of work addresses scene graph generation, little attention has been paid to optimizing the graph for consumption, which leaves state-of-the-art perception pipelines to work around their own scene graph and to pay a latency cost that does not fit the real-time budget a perception loop runs on. We present Yggdrasil, the first 3D scene graph designed to be efficient for both generation and consumption: a layer-first hierarchical graph built from generic nodes, edges, and layers, which expresses the representations existing pipelines already produce, indoor or outdoor, flat or hierarchical, while natively answering the positional and semantic queries downstream tasks issue. Against a published DSG baseline, Yggdrasil answers queries up to 121× faster, and every query we measure falls between 2 and 127 microseconds, three to five orders of magnitude inside the 200 microsecond keyframe budget a 3DSG consumer lives in, on both a workstation and embedded class device. We integrate Yggdrasil into three published pipelines spanning human trajectory prediction, object-goal navigation, and human-aware motion planning, where it removes up to 99% of the time each spends on its scene graph. The implementation, benchmark harness, and all three integrations are available online.

tags:
- Robotics
- 3D Scene Graphs
- Real-Time Systems

featured: false

url_pdf: 'https://arxiv.org/abs/2609.38640'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

projects: []
---
