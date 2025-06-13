---
layout: publication
title: 'Scaling LLM Pre-training With Vocabulary Curriculum'
authors: Fangyuan Yu
conference: "Arxiv"
year: 2025
bibkey: yu2025scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.17910"}
tags: ['Pre-Training', 'GPT', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Tokenization', 'Pretraining Methods']
---
Modern language models rely on static vocabularies, fixed before pretraining,
in contrast to the adaptive vocabulary acquisition observed in human language
learning. To bridge this gap, we introduce vocabulary curriculum learning, an
approach that improves pretraining efficiency with log-linear scaling gains
relative to vocabulary size. Our method alternates between entropy-guided
vocabulary expansion and model optimization, enabling models to learn
transferable representations across diverse tokenization granularities. This
approach naturally gives rise to an optimal computation allocation pattern:
longer tokens capture predictable content, while shorter tokens focus on more
complex, harder-to-predict contexts. Experiments on small-scale GPT models
demonstrate improved scaling efficiency, reinforcing the effectiveness of
dynamic tokenization. We release our code to support further research and plan
to extend our experiments to larger models and diverse domains.
