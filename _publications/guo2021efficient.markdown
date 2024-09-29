---
layout: publication
title: Longt5 Efficient Text-to-text Transformer For Long Sequences
authors: Guo Mandy, Ainslie Joshua, Uthus David, Ontanon Santiago, Ni Jianmo, Sung Yun-hsuan, Yang Yinfei
conference: "Arxiv"
year: 2021
bibkey: guo2021efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.07916"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Recent work has shown that either (1) increasing the input length or (2) increasing model size can improve the performance of Transformer-based neural models. In this paper we present a new model called LongT5 with which we explore the effects of scaling both the input length and model size at the same time. Specifically we integrated attention ideas from long-input transformers (ETC) and adopted pre-training strategies from summarization pre-training (PEGASUS) into the scalable T5 architecture. The result is a new attention mechanism we call (em) Transient Global (TGlobal) which mimics ETCs local/global attention mechanism but without requiring additional side-inputs. We are able to achieve state-of-the-art results on several summarization tasks and outperform the original T5 models on question answering tasks.
