---
layout: publication
title: 'Token Prepending: A Training-free Approach For Eliciting Better Sentence Embeddings From Llms'
authors: Yuchen Fu, Zifeng Cheng, Zhiwei Jiang, Zhonghui Wang, Yafeng Yin, Zhengliang Li, Qing Gu
conference: "Arxiv"
year: 2024
bibkey: fu2024token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.11556"}
tags: ['Transformer', 'GPT', 'Ethics and Bias', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Prompting']
---
Extracting sentence embeddings from large language models (LLMs) is a
promising direction, as LLMs have demonstrated stronger semantic understanding
capabilities. Previous studies typically focus on prompt engineering to elicit
sentence embeddings from LLMs by prompting the model to encode sentence
information into the embedding of the last token. However, LLMs are mostly
decoder-only models with causal attention and the earlier tokens in the
sentence cannot attend to the latter tokens, resulting in biased encoding of
sentence information and cascading effects on the final decoded token. To this
end, we propose a novel Token Prepending (TP) technique that prepends each
layer's decoded sentence embedding to the beginning of the sentence in the next
layer's input, allowing earlier tokens to attend to the complete sentence
information under the causal attention mechanism. The proposed TP technique is
a plug-and-play and training-free technique, which means it can be seamlessly
integrated with various prompt-based sentence embedding methods and
autoregressive LLMs. Extensive experiments on various Semantic Textual
Similarity (STS) tasks and downstream classification tasks demonstrate that our
proposed TP technique can significantly improve the performance of existing
prompt-based sentence embedding methods across different LLMs, while incurring
negligible additional inference cost.
