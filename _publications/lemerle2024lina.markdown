---
layout: publication
title: 'Lina-speech: Gated Linear Attention Is A Fast And Parameter-efficient Learner For Text-to-speech Synthesis'
authors: Théodor Lemerle, Harrison Vanderbyl, Vaibhav Srivastav, Nicolas Obin, Axel Roebel
conference: "Arxiv"
year: 2024
bibkey: lemerle2024lina
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.23320"}
  - {name: "Code", url: "https://theodorblackbird.github.io/blog/demo_lina/"}
tags: ['Transformer', 'GPT', 'RAG', 'Model Architecture', 'Merging', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Prompting']
---
Neural codec language models have achieved state-of-the-art performance in
text-to-speech (TTS) synthesis, leveraging scalable architectures like
autoregressive transformers and large-scale speech datasets. By framing voice
cloning as a prompt continuation task, these models excel at cloning voices
from short audio samples. However, this approach is limited in its ability to
handle numerous or lengthy speech excerpts, since the concatenation of source
and target speech must fall within the maximum context length which is
determined during training. In this work, we introduce Lina-Speech, a model
that replaces traditional self-attention mechanisms with emerging recurrent
architectures like Gated Linear Attention (GLA). Building on the success of
initial-state tuning on RWKV, we extend this technique to voice cloning,
enabling the use of multiple speech samples and full utilization of the context
window in synthesis. This approach is fast, easy to deploy, and achieves
performance comparable to fine-tuned baselines when the dataset size ranges
from 3 to 15 minutes. Notably, Lina-Speech matches or outperforms
state-of-the-art baseline models, including some with a parameter count up to
four times higher or trained in an end-to-end style. We release our code and
checkpoints. Audio samples are available at
https://theodorblackbird.github.io/blog/demo_lina/.
