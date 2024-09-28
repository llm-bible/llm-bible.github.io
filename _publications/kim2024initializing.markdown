---
layout: publication
title: On Initializing Transformers with Pre-trained Embeddings
authors: Kim Ha Young, Balasubramanian Niranjan, Kang Byungkon
conference: "Arxiv"
year: 2024
bibkey: kim2024initializing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12514"}
tags: ['ARXIV', 'BERT', 'Model Architecture', 'Transformer']
---
It has become common practice now to use random initialization schemes rather than the pre-trained embeddings when training transformer based models from scratch. Indeed we find that pre-trained word embeddings from GloVe and some sub-word embeddings extracted from language models such as T5 and mT5 fare much worse compared to random initialization. This is counter-intuitive given the well-known representational and transfer-learning advantages of pre-training. Interestingly we also find that BERT and mBERT embeddings fare better than random initialization showing the advantages of pre-trained representations. In this work we posit two potential factors that contribute to these mixed results the model sensitivity to parameter distribution and the embedding interactions with position encodings. We observe that pre-trained GloVe T5 and mT5 embeddings have a wider distribution of values. As argued in the initialization studies such large value initializations can lead to poor training because of saturated outputs. Further the larger embedding values can in effect absorb the smaller position encoding values when added together thus losing position information. Standardizing the pre-trained embeddings to a narrow range (e.g. as prescribed by Xavier) leads to substantial gains for Glove T5 and mT5 embeddings. On the other hand BERT pre-trained embeddings while larger are still relatively closer to Xavier initialization range which may allow it to effectively transfer the pre-trained knowledge.
