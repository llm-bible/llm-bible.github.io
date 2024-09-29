---
layout: publication
title: Generation45;distillation For Efficient Natural Language Understanding In Low45;data Settings
authors: Melas-kyriazi Luke, Han George, Liang Celine
conference: "Arxiv"
year: 2020
bibkey: melaskyriazi2020generation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2002.00733"}
tags: ['Applications', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'RAG', 'Training Techniques']
---
Over the past year the emergence of transfer learning with large45;scale language models (LM) has led to dramatic performance improvements across a broad range of natural language understanding tasks. However the size and memory footprint of these large LMs makes them difficult to deploy in many scenarios (e.g. on mobile phones). Recent research points to knowledge distillation as a potential solution showing that when training data for a given task is abundant it is possible to distill a large (teacher) LM into a small task45;specific (student) network with minimal loss of performance. However when such data is scarce there remains a significant performance gap between large pretrained LMs and smaller task45;specific models even when training via distillation. In this paper we bridge this gap with a novel training approach called generation45;distillation that leverages large finetuned LMs in two ways (1) to generate new (unlabeled) training examples and (2) to distill their knowledge into a small network using these examples. Across three low45;resource text classification datsets we achieve comparable performance to BERT while using 300x fewer parameters and we outperform prior approaches to distillation for text classification while using 3x fewer parameters.
