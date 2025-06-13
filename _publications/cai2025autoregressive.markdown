---
layout: publication
title: 'Autoregressive Image Generation With Vision Full-view Prompt'
authors: Miaomiao Cai, Guanjie Wang, Wei Li, Zhijun Tu, Hanting Chen, Shaohui Lin, Jie Hu
conference: "Arxiv"
year: 2025
bibkey: cai2025autoregressive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.16965'}
tags: ['RAG', 'GPT', 'Merging', 'Prompting', 'Ethics and Bias', 'Pretraining Methods']
---
In autoregressive (AR) image generation, models based on the 'next-token
prediction' paradigm of LLMs have shown comparable performance to diffusion
models by reducing inductive biases. However, directly applying LLMs to complex
image generation can struggle with reconstructing the image's structure and
details, impacting the generation's accuracy and stability. Additionally, the
'next-token prediction' paradigm in the AR model does not align with the
contextual scanning and logical reasoning processes involved in human visual
perception, limiting effective image generation. Prompt engineering, as a key
technique for guiding LLMs, leverages specifically designed prompts to improve
model performance on complex natural language processing (NLP) tasks, enhancing
accuracy and stability of generation while maintaining contextual coherence and
logical consistency, similar to human reasoning. Inspired by prompt engineering
from the field of NLP, we propose Vision Full-view prompt (VF prompt) to
enhance autoregressive image generation. Specifically, we design specialized
image-related VF prompts for AR image generation to simulate the process of
human image creation. This enhances contextual logic ability by allowing the
model to first perceive overall distribution information before generating the
image, and improve generation stability by increasing the inference steps.
Compared to the AR method without VF prompts, our method shows outstanding
performance and achieves an approximate improvement of 20%.
