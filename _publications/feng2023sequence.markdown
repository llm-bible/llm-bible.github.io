---
layout: publication
title: 'Sequence-to-sequence Pre-training With Unified Modality Masking For Visual Document Understanding'
authors: Shuwei Feng, Tianyang Zhan, Zhanming Jie, Trung Quoc Luong, Xiaoran Jin
conference: "Arxiv"
year: 2023
bibkey: feng2023sequence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.10448"}
tags: ['Pre-Training', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism']
---
This paper presents GenDoc, a general sequence-to-sequence document
understanding model pre-trained with unified masking across three modalities:
text, image, and layout. The proposed model utilizes an encoder-decoder
architecture, which allows for increased adaptability to a wide range of
downstream tasks with diverse output formats, in contrast to the encoder-only
models commonly employed in document understanding. In addition to the
traditional text infilling task used in previous encoder-decoder models, our
pre-training extends to include tasks of masked image token prediction and
masked layout prediction. We also design modality-specific instruction and
adopt both disentangled attention and the mixture-of-modality-experts strategy
to effectively capture the information leveraged by each modality. Evaluation
of the proposed model through extensive experiments on several downstream tasks
in document understanding demonstrates its ability to achieve superior or
competitive performance compared to state-of-the-art approaches. Our analysis
further suggests that GenDoc is more robust than the encoder-only models in
scenarios where the OCR quality is imperfect.
