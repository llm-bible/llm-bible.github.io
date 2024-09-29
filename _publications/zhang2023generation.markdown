---
layout: publication
title: "Generation-driven Contrastive Self-training For Zero-shot Text Classification With Instruction-following LLM"
authors: Zhang Ruohong, Wang Yau-shian, Yang Yiming
conference: "Arxiv"
year: 2023
bibkey: zhang2023generation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.11872"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
The remarkable performance of large language models (LLMs) in zero-shot language understanding has garnered significant attention. However employing LLMs for large-scale inference or domain-specific fine-tuning requires immense computational resources due to their substantial model size. To overcome these limitations we introduce a novel method namely GenCo which leverages the strong generative power of LLMs to assist in training a smaller and more adaptable language model. In our method an LLM plays an important role in the self-training loop of a smaller model in two important ways. Firstly the LLM is used to augment each input instance with a variety of possible continuations enriching its semantic context for better understanding. Secondly it helps crafting additional high-quality training pairs by rewriting input texts conditioned on predicted labels. This ensures the generated texts are highly relevant to the predicted labels alleviating the prediction error during pseudo-labeling while reducing the dependency on large volumes of unlabeled text. In our experiments GenCo outperforms previous state-of-the-art methods when only limited (<537; of original) in-domain text data is available. Notably our approach surpasses the performance of Alpaca-7B with human prompts highlighting the potential of leveraging LLM for self-training.
