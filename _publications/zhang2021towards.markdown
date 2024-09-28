---
layout: publication
title: Towards More Efficient Insertion Transformer with Fractional Positional Encoding
authors: Zhang Zhisong, Zhang Yizhe, Dolan Bill
conference: "Arxiv"
year: 2021
bibkey: zhang2021towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.06295"}
tags: ['ARXIV', 'Language Modeling', 'Model Architecture', 'Transformer']
---
Auto-regressive neural sequence models have been shown to be effective across text generation tasks. However their left-to-right decoding order prevents generation from being parallelized. Insertion Transformer (Stern et al. 2019) is an attractive alternative that allows outputting multiple tokens in a single generation step. Nevertheless due to the incompatibility between absolute positional encoding and insertion-based generation schemes it needs to refresh the encoding of every token in the generated partial hypothesis at each step which could be costly. We design a novel reusable positional encoding scheme for Insertion Transformers called Fractional Positional Encoding (FPE) which allows reusing representations calculated in previous steps. Empirical studies on various text generation tasks demonstrate the effectiveness of FPE which leads to floating-point operation reduction and latency improvements on batched decoding.
