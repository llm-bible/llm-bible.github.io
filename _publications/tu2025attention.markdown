---
layout: publication
title: 'Attention Reallocation: Towards Zero-cost And Controllable Hallucination Mitigation Of Mllms'
authors: Chongjun Tu, Peng Ye, Dongzhan Zhou, Lei Bai, Gang Yu, Tao Chen, Wanli Ouyang
conference: "Arxiv"
year: 2025
bibkey: tu2025attention
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.08342'}
tags: ['Attention Mechanism', 'Training Techniques', 'Reinforcement Learning', 'Model Architecture']
---
Multi-Modal Large Language Models (MLLMs) stand out in various tasks but
still struggle with hallucinations. While recent training-free mitigation
methods mostly introduce additional inference overhead via retrospection
strategy and contrastive decoding, we propose attention reallocation (AttnReal)
to mitigate hallucinations with nearly zero extra cost. Our approach is
motivated by the key observations that, MLLM's unreasonable attention
distribution causes features to be dominated by historical output tokens, which
further contributes to hallucinated responses because of the distribution gap
between different token types. Based on the observations, AttnReal recycles
excessive attention from output tokens and reallocates it to visual tokens,
which reduces MLLM's reliance on language priors and ensures the decoding
process depends more on the visual inputs. More interestingly, we find that, by
controlling the intensity of AttnReal, we can achieve a wide-range trade-off
between the response faithfulness and overall performance. Comprehensive
results from different benchmarks validate the effectiveness of AttnReal across
six open-source MLLMs and three decoding strategies.
