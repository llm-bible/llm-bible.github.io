---
layout: publication
title: Recoverable Compression A Multimodal Vision Token Recovery Mechanism Guided By Text Information
authors: Chen Yi, Xu Jian, Zhang Xu-yao, Liu Wen-zhuo, Liu Yang-yang, Liu Cheng-lin
conference: "Arxiv"
year: 2024
bibkey: chen2024recoverable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01179"}
tags: ['Efficiency And Optimization', 'Language Modeling', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Pruning', 'RAG', 'Training Techniques', 'Transformer']
---
With the advancement of large45;scale language modeling techniques large multimodal models combining visual encoders with large language models have demonstrated exceptional performance in various visual tasks. Most of the current large45;scale multimodal models achieve this by mapping visual features obtained from the visual encoder into a large language model and using them as inputs alongside text for downstream tasks. Therefore the number of visual tokens directly affects the training and inference speed of the model. There has been significant work on token pruning for visual transformers but for large multimodal models only relying on visual information for token pruning or compression may lead to significant loss of important information. On the other hand the textual input in the form of a question may contain valuable information that can aid in answering the question providing additional knowledge to the model. To address the potential oversimplification and excessive pruning that can occur with most purely visual token pruning methods we propose a text information45;guided dynamic visual token recovery mechanism that does not require training. This mechanism leverages the similarity between the question text and visual tokens to recover visually meaningful tokens with important text information while merging other less important tokens. Experimental results demonstrate that our proposed method achieves comparable performance to the original approach while compressing the visual tokens to an average of 1037; of the original quantity. Our source code will be made publicly available following acceptance.
