---
layout: publication
title: 'Nextlong: Toward Effective Long-context Training Without Long Documents'
authors: Chaochen Gao, Xing Wu, Zijia Lin, Debing Zhang, Songlin Hu
conference: "Arxiv"
year: 2025
bibkey: gao2025toward
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.12766'}
tags: ['Reinforcement Learning', 'Training Techniques', 'Tools', 'Pretraining Methods']
---
Large language models (LLMs) with extended context windows have made significant strides yet remain a challenge due to the scarcity of long documents. Existing methods tend to synthesize long-context data but lack a clear mechanism to reinforce the long-range dependency modeling. To address this limitation, we propose NExtLong, a novel framework for synthesizing long-context data through Negative document Extension. NExtLong decomposes a document into multiple meta-chunks and extends the context by interleaving hard negative distractors retrieved from pretraining corpora. This approach compels the model to discriminate long-range dependent context from distracting content, enhancing its ability to model long-range dependencies. Extensive experiments demonstrate that NExtLong achieves significant performance improvements on the HELMET and RULER benchmarks compared to existing long-context synthesis approaches and leading models, which are trained on non-synthetic long documents. These findings highlight NExtLong's ability to reduce reliance on non-synthetic long documents, making it an effective framework for developing advanced long-context LLMs.
