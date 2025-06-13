---
layout: publication
title: 'Vid-gpt: Introducing Gpt-style Autoregressive Generation In Video Diffusion Models'
authors: Kaifeng Gao, Jiaxin Shi, Hanwang Zhang, Chunping Wang, Jun Xiao
conference: "Arxiv"
year: 2024
bibkey: gao2024vid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10981"}
  - {name: "Code", url: "https://github.com/Dawn-LX/Causal-VideoGen"}
tags: ['Transformer', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Prompting']
---
With the advance of diffusion models, today's video generation has achieved
impressive quality. But generating temporal consistent long videos is still
challenging. A majority of video diffusion models (VDMs) generate long videos
in an autoregressive manner, i.e., generating subsequent clips conditioned on
last frames of previous clip. However, existing approaches all involve
bidirectional computations, which restricts the receptive context of each
autoregression step, and results in the model lacking long-term dependencies.
Inspired from the huge success of large language models (LLMs) and following
GPT (generative pre-trained transformer), we bring causal (i.e.,
unidirectional) generation into VDMs, and use past frames as prompt to generate
future frames. For Causal Generation, we introduce causal temporal attention
into VDM, which forces each generated frame to depend on its previous frames.
For Frame as Prompt, we inject the conditional frames by concatenating them
with noisy frames (frames to be generated) along the temporal axis.
Consequently, we present Video Diffusion GPT (ViD-GPT). Based on the two key
designs, in each autoregression step, it is able to acquire long-term context
from prompting frames concatenated by all previously generated frames.
Additionally, we bring the kv-cache mechanism to VDMs, which eliminates the
redundant computation from overlapped frames, significantly boosting the
inference speed. Extensive experiments demonstrate that our ViD-GPT achieves
state-of-the-art performance both quantitatively and qualitatively on long
video generation. Code will be available at
https://github.com/Dawn-LX/Causal-VideoGen.
