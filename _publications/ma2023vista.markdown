---
layout: publication
title: 'Vista-llama: Reducing Hallucination In Video Language Models Via Equal Distance To Visual Tokens'
authors: Fan Ma, Xiaojie Jin, Heng Wang, Yuchen Xian, Jiashi Feng, Yi Yang
conference: "Arxiv"
year: 2023
bibkey: ma2023vista
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.08870'}
tags: ['Attention Mechanism', 'Transformer', 'GPT', 'Model Architecture', 'Tools', 'Applications']
---
Recent advances in large video-language models have displayed promising
outcomes in video comprehension. Current approaches straightforwardly convert
video into language tokens and employ large language models for multi-modal
tasks. However, this method often leads to the generation of irrelevant
content, commonly known as "hallucination", as the length of the text increases
and the impact of the video diminishes. To address this problem, we propose
Vista-LLaMA, a novel framework that maintains the consistent distance between
all visual tokens and any language tokens, irrespective of the generated text
length. Vista-LLaMA omits relative position encoding when determining attention
weights between visual and text tokens, retaining the position encoding for
text and text tokens. This amplifies the effect of visual tokens on text
generation, especially when the relative distance is longer between visual and
text tokens. The proposed attention mechanism significantly reduces the chance
of producing irrelevant text related to the video content. Furthermore, we
present a sequential visual projector that projects the current video frame
into tokens of language space with the assistance of the previous frame. This
approach not only captures the temporal relationship within the video, but also
allows less visual tokens to encompass the entire video. Our approach
significantly outperforms various previous methods (e.g., Video-ChatGPT,
MovieChat) on four challenging open-ended video question answering benchmarks.
We reach an accuracy of 60.7 on the zero-shot NExT-QA and 60.5 on the zero-shot
MSRVTT-QA, setting a new state-of-the-art performance. This project is
available at https://jinxxian.github.io/Vista-LLaMA.
