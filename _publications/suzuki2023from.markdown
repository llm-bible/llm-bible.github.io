---
layout: publication
title: From Base To Conversational Japanese Instruction Dataset And Tuning Large Language Models
authors: Suzuki Masahiro, Hirano Masanori, Sakaji Hiroki
conference: "Arxiv"
year: 2023
bibkey: suzuki2023from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.03412"}
tags: ['Fine Tuning', 'Pretraining Methods']
---
Instruction tuning is essential for large language models (LLMs) to become interactive. While many instruction tuning datasets exist in English there is a noticeable lack in other languages. Also their effectiveness has not been well verified in non-English languages. We construct a Japanese instruction dataset by expanding and filtering existing datasets and apply the dataset to a Japanese pre-trained base model. We performed Low-Rank Adaptation (LoRA) tuning on both Japanese and English existing models using our instruction dataset. We evaluated these models from both quantitative and qualitative perspectives. As a result the effectiveness of Japanese instruction datasets is confirmed. The results also indicate that even with relatively small LLMs performances in downstream tasks would be improved through instruction tuning. Our instruction dataset tuned models and implementation are publicly available online.
