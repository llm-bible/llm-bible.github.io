---
layout: publication
title: LOCOST State45;space Models For Long Document Abstractive Summarization
authors: Bronnec Florian Le, Duong Song, Ravaut Mathieu, Allauzen Alexandre, Chen Nancy F., Guigue Vincent, Lumbreras Alberto, Soulier Laure, Gallinari Patrick
conference: "Arxiv"
year: 2024
bibkey: bronnec2024state
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.17919"}
tags: ['Applications', 'Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
State45;space models are a low45;complexity alternative to transformers for encoding long sequences and capturing long45;term dependencies. We propose LOCOST an encoder45;decoder architecture based on state45;space models for conditional text generation with long context inputs. With a computational complexity of O(L log L) this architecture can handle significantly longer sequences than state45;of45;the45;art models that are based on sparse attention patterns. We evaluate our model on a series of long document abstractive summarization tasks. The model reaches a performance level that is 9345;9637; comparable to the top45;performing sparse transformers of the same size while saving up to 5037; memory during training and up to 8737; during inference. Additionally LOCOST effectively handles input texts exceeding 600K tokens at inference time setting new state45;of45;the45;art results on full45;book summarization and opening new perspectives for long input processing.
