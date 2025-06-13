---
layout: publication
title: 'Benchmarking Zero-shot Stance Detection With Flant5-xxl: Insights From Training Data, Prompting, And Decoding Strategies Into Its Near-sota Performance'
authors: Rachith Aiyappa, Shruthi Senthilmani, Jisun An, Haewoon Kwak, Yong-yeol Ahn
conference: "Arxiv"
year: 2024
bibkey: aiyappa2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.00236"}
tags: ['Prompting', 'Ethics and Bias', 'Training Techniques', 'Reinforcement Learning']
---
We investigate the performance of LLM-based zero-shot stance detection on
tweets. Using FlanT5-XXL, an instruction-tuned open-source LLM, with the
SemEval 2016 Tasks 6A, 6B, and P-Stance datasets, we study the performance and
its variations under different prompts and decoding strategies, as well as the
potential biases of the model. We show that the zero-shot approach can match or
outperform state-of-the-art benchmarks, including fine-tuned models. We provide
various insights into its performance including the sensitivity to instructions
and prompts, the decoding strategies, the perplexity of the prompts, and to
negations and oppositions present in prompts. Finally, we ensure that the LLM
has not been trained on test datasets, and identify a positivity bias which may
partially explain the performance differences across decoding strategie
