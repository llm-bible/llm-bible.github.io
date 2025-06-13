---
layout: publication
title: 'Deepening Hidden Representations From Pre-trained Language Models'
authors: Junjie Yang, Hai Zhao
conference: "Arxiv"
year: 2019
bibkey: yang2019deepening
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1911.01940"}
tags: ['Training Techniques', 'Model Architecture', 'Pretraining Methods', 'BERT', 'Transformer', 'Fine-Tuning']
---
Transformer-based pre-trained language models have proven to be effective for
learning contextualized language representation. However, current approaches
only take advantage of the output of the encoder's final layer when fine-tuning
the downstream tasks. We argue that only taking single layer's output restricts
the power of pre-trained representation. Thus we deepen the representation
learned by the model by fusing the hidden representation in terms of an
explicit HIdden Representation Extractor (HIRE), which automatically absorbs
the complementary representation with respect to the output from the final
layer. Utilizing RoBERTa as the backbone encoder, our proposed improvement over
the pre-trained models is shown effective on multiple natural language
understanding tasks and help our model rival with the state-of-the-art models
on the GLUE benchmark.
