---
layout: publication
title: Telling Bert's Full Story\: From Local Attention To Global Aggregation
authors: Pascual Damian, Brunner Gino, Wattenhofer Roger
conference: "Arxiv"
year: 2020
bibkey: pascual2020telling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.05916"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
We take a deep look into the behavior of self-attention heads in the transformer architecture. In light of recent work discouraging the use of attention distributions for explaining a models behavior we show that attention distributions can nevertheless provide insights into the local behavior of attention heads. This way we propose a distinction between local patterns revealed by attention and global patterns that refer back to the input and analyze BERT from both angles. We use gradient attribution to analyze how the output of an attention attention head depends on the input tokens effectively extending the local attention-based analysis to account for the mixing of information throughout the transformer layers. We find that there is a significant discrepancy between attention and attribution distributions caused by the mixing of context inside the model. We quantify this discrepancy and observe that interestingly there are some patterns that persist across all layers despite the mixing.
