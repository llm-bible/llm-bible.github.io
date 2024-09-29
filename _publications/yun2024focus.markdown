---
layout: publication
title: Focus on the Core Efficient Attention via Pruned Token Compression for Document Classification
authors: Yun Jungmin, Kim Mihyeon, Kim Youngbin
conference: "Arxiv"
year: 2024
bibkey: yun2024focus
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01283"}
tags: ['Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Transformer']
---
Transformer-based models have achieved dominant performance in numerous NLP tasks. Despite their remarkable successes pre-trained transformers such as BERT suffer from a computationally expensive self-attention mechanism that interacts with all tokens including the ones unfavorable to classification performance. To overcome these challenges we propose integrating two strategies token pruning and token combining. Token pruning eliminates less important tokens in the attention mechanisms key and value as they pass through the layers. Additionally we adopt fuzzy logic to handle uncertainty and alleviate potential mispruning risks arising from an imbalanced distribution of each tokens importance. Token combining on the other hand condenses input sequences into smaller sizes in order to further compress the model. By integrating these two approaches we not only improve the models performance but also reduce its computational demands. Experiments with various datasets demonstrate superior performance compared to baseline models especially with the best improvement over the existing BERT model achieving +5p in accuracy and +5.6p in F1 score. Additionally memory cost is reduced to 0.61x and a speedup of 1.64x is achieved.
