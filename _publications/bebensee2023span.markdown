---
layout: publication
title: 'Span-selective Linear Attention Transformers For Effective And Robust Schema-guided Dialogue State Tracking'
authors: Bebensee Björn, Lee Haejun
conference: "Arxiv"
year: 2023
bibkey: bebensee2023span
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.09340"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques', 'Transformer']
---
In schema-guided dialogue state tracking models estimate the current state of
a conversation using natural language descriptions of the service schema for
generalization to unseen services. Prior generative approaches which decode
slot values sequentially do not generalize well to variations in schema, while
discriminative approaches separately encode history and schema and fail to
account for inter-slot and intent-slot dependencies. We introduce SPLAT, a
novel architecture which achieves better generalization and efficiency than
prior approaches by constraining outputs to a limited prediction space. At the
same time, our model allows for rich attention among descriptions and history
while keeping computation costs constrained by incorporating linear-time
attention. We demonstrate the effectiveness of our model on the Schema-Guided
Dialogue (SGD) and MultiWOZ datasets. Our approach significantly improves upon
existing models achieving 85.3 JGA on the SGD dataset. Further, we show
increased robustness on the SGD-X benchmark: our model outperforms the more
than 30\\(\times\\) larger D3ST-XXL model by 5.0 points.
