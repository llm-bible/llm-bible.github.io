---
layout: publication
title: 'Beyond Intermediate States: Explaining Visual Redundancy Through Language'
authors: Dingchen Yang, Bowen Cao, Anran Zhang, Weibo Gu, Winston Hu, Guang Chen
conference: "Arxiv"
year: 2025
bibkey: yang2025beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.20540'}
tags: ['Attention Mechanism', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pruning']
---
Multi-modal Large Langue Models (MLLMs) often process thousands of visual
tokens, which consume a significant portion of the context window and impose a
substantial computational burden. Prior work has empirically explored visual
token pruning methods based on MLLMs' intermediate states (e.g., attention
scores). However, they have limitations in precisely defining visual redundancy
due to their inability to capture the influence of visual tokens on MLLMs'
visual understanding (i.e., the predicted probabilities for textual token
candidates). To address this issue, we manipulate the visual input and
investigate variations in the textual output from both token-centric and
context-centric perspectives, achieving intuitive and comprehensive analysis.
Experimental results reveal that visual tokens with low ViT-[cls] association
and low text-to-image attention scores can contain recognizable information and
significantly contribute to images' overall information. To develop a more
reliable method for identifying and pruning redundant visual tokens, we
integrate these two perspectives and introduce a context-independent condition
to identify redundant prototypes from training images, which probes the
redundancy of each visual token during inference. Extensive experiments on
single-image, multi-image and video comprehension tasks demonstrate the
effectiveness of our method, notably achieving 90% to 110% of the performance
while pruning 80% to 90% of visual tokens.
