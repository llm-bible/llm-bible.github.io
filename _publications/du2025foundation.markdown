---
layout: publication
title: 'Graphoracle: A Foundation Model For Knowledge Graph Reasoning'
authors: Enjun Du, Siyi Liu, Yongqi Zhang
conference: "Arxiv"
year: 2025
bibkey: du2025foundation
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.11125'}
tags: ['Attention Mechanism', 'Transformer', 'ACL', 'Training Techniques', 'Model Architecture', 'Applications', 'Fine-Tuning', 'Pre-Training', 'Pretraining Methods']
---
Foundation models have demonstrated remarkable capabilities across various domains, but developing analogous models for knowledge graphs presents unique challenges due to their dynamic nature and the need for cross-domain reasoning. To address these issues, we introduce \textbf\{\textsc\{GraphOracle\}\}, a relation-centric foundation model that unifies reasoning across knowledge graphs by converting them into Relation-Dependency Graphs (RDG), explicitly encoding compositional patterns with fewer edges than prior methods. A query-dependent attention mechanism is further developed to learn inductive representations for both relations and entities. Pre-training on diverse knowledge graphs, followed by minutes-level fine-tuning, enables effective generalization to unseen entities, relations, and entire graphs. Through comprehensive experiments on 31 diverse benchmarks spanning transductive, inductive, and cross-domain settings, we demonstrate consistent state-of-the-art performance with minimal adaptation, improving the prediction performance by up to 35% compared to the strongest baselines.
