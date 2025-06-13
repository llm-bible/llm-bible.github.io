---
layout: publication
title: 'Revealing The Inherent Instructability Of Pre-trained Language Models'
authors: Seokhyun An, Minji Kim, Hyounghun Kim
conference: "Arxiv"
year: 2024
bibkey: an2024revealing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.02465'}
tags: ['Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pre-Training', 'In-Context Learning', 'Pretraining Methods']
---
Instruction tuning -- supervised fine-tuning using instruction-response pairs
-- is a key step in making pre-trained large language models (LLMs)
instructable. Meanwhile, LLMs perform multitask learning during their
pre-training, acquiring extensive knowledge and capabilities. We hypothesize
that the pre-training stage can enable them to develop the ability to
comprehend and address instructions. To verify this, we propose Response Tuning
(RT), which removes the instruction and its corresponding mapping to the
response from instruction tuning. Instead, it focuses solely on establishing
the response distribution. Our experiments demonstrate that RT models, trained
only on responses, can effectively respond to a wide range of instructions and
exhibit helpfulness approaching that of their instruction-tuned counterparts.
In addition, we observe that the models can recognize and reject unsafe queries
after learning the refusal conditions from training responses. Furthermore, we
demonstrate that these observations also hold in an in-context learning
setting. These findings support our hypothesis, highlighting the extensive
inherent capabilities of pre-trained LLMs.
