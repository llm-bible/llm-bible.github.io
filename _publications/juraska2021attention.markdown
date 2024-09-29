---
layout: publication
title: "Attention Is Indeed All You Need: Semantically Attention-guided Decoding For Data-to-text NLG"
authors: Juraska Juraj, Walker Marilyn
conference: "Arxiv"
year: 2021
bibkey: juraska2021attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.07043"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture']
---
Ever since neural models were adopted in data-to-text language generation they have invariably been reliant on extrinsic components to improve their semantic accuracy because the models normally do not exhibit the ability to generate text that reliably mentions all of the information provided in the input. In this paper we propose a novel decoding method that extracts interpretable information from encoder-decoder models cross-attention and uses it to infer which attributes are mentioned in the generated text which is subsequently used to rescore beam hypotheses. Using this decoding method with T5 and BART we show on three datasets its ability to dramatically reduce semantic errors in the generated outputs while maintaining their state-of-the-art quality.
