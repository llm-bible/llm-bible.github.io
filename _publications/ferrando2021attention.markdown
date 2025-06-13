---
layout: publication
title: 'Attention Weights In Transformer NMT Fail Aligning Words Between Sequences But Largely Explain Model Predictions'
authors: Javier Ferrando, Marta R. Costa-jussà
conference: "Arxiv"
year: 2021
bibkey: ferrando2021attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.05853"}
tags: ['Model Architecture', 'Pretraining Methods', 'Transformer', 'Interpretability and Explainability', 'Applications', 'Attention Mechanism']
---
This work proposes an extensive analysis of the Transformer architecture in
the Neural Machine Translation (NMT) setting. Focusing on the encoder-decoder
attention mechanism, we prove that attention weights systematically make
alignment errors by relying mainly on uninformative tokens from the source
sequence. However, we observe that NMT models assign attention to these tokens
to regulate the contribution in the prediction of the two contexts, the source
and the prefix of the target sequence. We provide evidence about the influence
of wrong alignments on the model behavior, demonstrating that the
encoder-decoder attention mechanism is well suited as an interpretability
method for NMT. Finally, based on our analysis, we propose methods that largely
reduce the word alignment error rate compared to standard induced alignments
from attention weights.
