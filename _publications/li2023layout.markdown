---
layout: publication
title: 'LANS: A Layout-aware Neural Solver For Plane Geometry Problem'
authors: Zhong-zhi Li, Ming-liang Zhang, Fei Yin, Cheng-lin Liu
conference: "Arxiv"
year: 2023
bibkey: li2023layout
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.16476"}
tags: ['Pre-Training', 'Model Architecture', 'Merging', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models']
---
Geometry problem solving (GPS) is a challenging mathematical reasoning task
requiring multi-modal understanding, fusion, and reasoning. Existing neural
solvers take GPS as a vision-language task but are short in the representation
of geometry diagrams that carry rich and complex layout information. In this
paper, we propose a layout-aware neural solver named LANS, integrated with two
new modules: multimodal layout-aware pre-trained language module (MLA-PLM) and
layout-aware fusion attention (LA-FA). MLA-PLM adopts structural-semantic
pre-training (SSP) to implement global relationship modeling, and point-match
pre-training (PMP) to achieve alignment between visual points and textual
points. LA-FA employs a layout-aware attention mask to realize point-guided
cross-modal fusion for further boosting layout awareness of LANS. Extensive
experiments on datasets Geometry3K and PGPS9K validate the effectiveness of the
layout-aware modules and superior problem-solving performance of our LANS
solver, over existing symbolic and neural solvers. The code will be made public
available soon.
