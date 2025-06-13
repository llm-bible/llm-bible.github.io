---
layout: publication
title: 'Mimir: Improving Video Diffusion Models For Precise Text Understanding'
authors: Shuai Tan, Biao Gong, Yutong Feng, Kecheng Zheng, Dandan Zheng, Shuwei Shi, Yujun Shen, Jingdong Chen, Ming Yang
conference: "Arxiv"
year: 2024
bibkey: tan2024improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.03085'}
  - {name: "Code", url: 'https://lucaria-academy.github.io/Mimir/'}
tags: ['Has Code', 'Transformer', 'RAG', 'Training Techniques', 'Model Architecture', 'Tools', 'Merging', 'Pretraining Methods']
---
Text serves as the key control signal in video generation due to its
narrative nature. To render text descriptions into video clips, current video
diffusion models borrow features from text encoders yet struggle with limited
text comprehension. The recent success of large language models (LLMs)
showcases the power of decoder-only transformers, which offers three clear
benefits for text-to-video (T2V) generation, namely, precise text understanding
resulting from the superior scalability, imagination beyond the input text
enabled by next token prediction, and flexibility to prioritize user interests
through instruction tuning. Nevertheless, the feature distribution gap emerging
from the two different text modeling paradigms hinders the direct use of LLMs
in established T2V models. This work addresses this challenge with Mimir, an
end-to-end training framework featuring a carefully tailored token fuser to
harmonize the outputs from text encoders and LLMs. Such a design allows the T2V
model to fully leverage learned video priors while capitalizing on the
text-related capability of LLMs. Extensive quantitative and qualitative results
demonstrate the effectiveness of Mimir in generating high-quality videos with
excellent text comprehension, especially when processing short captions and
managing shifting motions. Project page:
https://lucaria-academy.github.io/Mimir/
