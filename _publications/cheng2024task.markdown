---
layout: publication
title: 'Task Arithmetic For Language Expansion In Speech Translation'
authors: Yao-fei Cheng, Hayato Futami, Yosuke Kashiwagi, Emiru Tsunoo, Wen Shen Teo, Siddhant Arora, Shinji Watanabe
conference: "Arxiv"
year: 2024
bibkey: cheng2024task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.11274"}
tags: ['Multimodal Models', 'Training Techniques', 'Tools', 'Merging', 'Applications']
---
Recent progress in large language models (LLMs) has gained interest in speech-text multimodal foundation models, achieving strong performance on instruction-tuned speech translation (ST). However, expanding language pairs is costly due to re-training on combined new and previous datasets. To address this, we aim to build a one-to-many ST system from existing one-to-one ST systems using task arithmetic without re-training. Direct application of task arithmetic in ST leads to language confusion; therefore, we introduce an augmented task arithmetic method incorporating a language control model to ensure correct target language generation. Our experiments on MuST-C and CoVoST-2 show BLEU score improvements of up to 4.66 and 4.92, with COMET gains of 8.87 and 11.83. In addition, we demonstrate our framework can extend to language pairs lacking paired ST training data or pre-trained ST models by synthesizing ST models based on existing machine translation (MT) and ST models via task analogies.
