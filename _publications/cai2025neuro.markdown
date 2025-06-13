---
layout: publication
title: 'NAVER: A Neuro-symbolic Compositional Automaton For Visual Grounding With Explicit Logic Reasoning'
authors: Zhixi Cai, Fucai Ke, Simindokht Jahangard, Maria Garcia De La Banda, Reza Haffari, Peter J. Stuckey, Hamid Rezatofighi
conference: "Arxiv"
year: 2025
bibkey: cai2025neuro
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.00372"}
  - {name: "Code", url: "https://github.com/ControlNet/NAVER"}
tags: ['Interpretability and Explainability', 'Security', 'Multimodal Models', 'Has Code']
---
Visual Grounding (VG) tasks, such as referring expression detection and
segmentation tasks are important for linking visual entities to context,
especially in complex reasoning tasks that require detailed query
interpretation. This paper explores VG beyond basic perception, highlighting
challenges for methods that require reasoning like human cognition. Recent
advances in large language methods (LLMs) and Vision-Language methods (VLMs)
have improved abilities for visual comprehension, contextual understanding, and
reasoning. These methods are mainly split into end-to-end and compositional
methods, with the latter offering more flexibility. Compositional approaches
that integrate LLMs and foundation models show promising performance but still
struggle with complex reasoning with language-based logical representations. To
address these limitations, we propose NAVER, a compositional visual grounding
method that integrates explicit probabilistic logic reasoning within a
finite-state automaton, equipped with a self-correcting mechanism. This design
improves robustness and interpretability in inference through explicit logic
reasoning. Our results show that NAVER achieves SoTA performance comparing to
recent end-to-end and compositional baselines. The code is available at
https://github.com/ControlNet/NAVER .
