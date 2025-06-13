---
layout: publication
title: 'Semformer: Transformer Language Models With Semantic Planning'
authors: Yongjing Yin, Junran Ding, Kai Song, Yue Zhang
conference: "EMNLP2024"
year: 2024
bibkey: yin2024transformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.11143"}
tags: ['Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Prompting', 'Applications', 'In-Context Learning']
---
Next-token prediction serves as the dominant component in current neural
language models. During the training phase, the model employs teacher forcing,
which predicts tokens based on all preceding ground truth tokens. However, this
approach has been found to create shortcuts, utilizing the revealed prefix to
spuriously fit future tokens, potentially compromising the accuracy of the
next-token predictor. In this paper, we introduce Semformer, a novel method of
training a Transformer language model that explicitly models the semantic
planning of response. Specifically, we incorporate a sequence of planning
tokens into the prefix, guiding the planning token representations to predict
the latent semantic representations of the response, which are induced by an
autoencoder. In a minimal planning task (i.e., graph path-finding), our model
exhibits near-perfect performance and effectively mitigates shortcut learning,
a feat that standard training methods and baseline models have been unable to
accomplish. Furthermore, we pretrain Semformer from scratch with 125M
parameters, demonstrating its efficacy through measures of perplexity,
in-context learning, and fine-tuning on summarization tasks.
