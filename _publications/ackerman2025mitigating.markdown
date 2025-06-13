---
layout: publication
title: 'Mitigating Many-shot Jailbreaking'
authors: Christopher M. Ackerman, Nina Panickssery
conference: "Arxiv"
year: 2025
bibkey: ackerman2025mitigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.09604'}
tags: ['In-Context Learning', 'Security', 'Training Techniques', 'Prompting', 'Fine-Tuning', 'Responsible AI', 'Pretraining Methods']
---
Many-shot jailbreaking (MSJ) is an adversarial technique that exploits the long context windows of modern LLMs to circumvent model safety training by including in the prompt many examples of a "fake" assistant responding inappropriately before the final request. With enough examples, the model's in-context learning abilities override its safety training, and it responds as if it were the "fake" assistant. In this work, we probe the effectiveness of different fine-tuning and input sanitization approaches on mitigating MSJ attacks, alone and in combination. We find incremental mitigation effectiveness for each, and show that the combined techniques significantly reduce the effectiveness of MSJ attacks, while retaining model performance in benign in-context learning and conversational tasks. We suggest that our approach could meaningfully ameliorate this vulnerability if incorporated into model safety post-training.
