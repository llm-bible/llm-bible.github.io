---
layout: publication
title: 'Elucidating The Design Space Of Language Models For Image Generation'
authors: Xuantong Liu, Shaozhe Hao, Xianbiao Qi, Tianyang Hu, Jun Wang, Rong Xiao, Yuan Yao
conference: "Arxiv"
year: 2024
bibkey: liu2024elucidating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16257"}
  - {name: "Code", url: "https://github.com/Pepperlll/LMforImageGeneration.git"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Language Modeling', 'GPT', 'Pretraining Methods', 'Has Code', 'Applications']
---
The success of autoregressive (AR) language models in text generation has
inspired the computer vision community to adopt Large Language Models (LLMs)
for image generation. However, considering the essential differences between
text and image modalities, the design space of language models for image
generation remains underexplored. We observe that image tokens exhibit greater
randomness compared to text tokens, which presents challenges when training
with token prediction. Nevertheless, AR models demonstrate their potential by
effectively learning patterns even from a seemingly suboptimal optimization
problem. Our analysis also reveals that while all models successfully grasp the
importance of local information in image generation, smaller models struggle to
capture the global context. In contrast, larger models showcase improved
capabilities in this area, helping to explain the performance gains achieved
when scaling up model size. We further elucidate the design space of language
models for vision generation, including tokenizer choice, model choice, model
scalability, vocabulary design, and sampling strategy through extensive
comparative experiments. Our work is the first to analyze the optimization
behavior of language models in vision generation, and we believe it can inspire
more effective designs when applying LMs to other domains. Finally, our
elucidated language model for image generation, termed as ELM, achieves
state-of-the-art performance on the ImageNet 256*256 benchmark. The code is
available at https://github.com/Pepperlll/LMforImageGeneration.git.
