---
layout: publication
title: 'How Well Can Vision Language Models See Image Details?'
authors: Chenhui Gou, Abdulwahab Felemban, Faizan Farooq Khan, Deyao Zhu, Jianfei Cai, Hamid Rezatofighi, Mohamed Elhoseiny
conference: "Arxiv"
year: 2024
bibkey: gou2024how
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.03940'}
tags: ['RAG', 'Training Techniques', 'Fine-Tuning', 'Multimodal Models', 'Pre-Training', 'Interpretability', 'Pretraining Methods']
---
Large Language Model-based Vision-Language Models (LLM-based VLMs) have
demonstrated impressive results in various vision-language understanding tasks.
However, how well these VLMs can see image detail beyond the semantic level
remains unclear. In our study, we introduce a pixel value prediction task (PVP)
to explore "How Well Can Vision Language Models See Image Details?" and to
assist VLMs in perceiving more details. Typically, these models comprise a
frozen CLIP visual encoder, a large language model, and a connecting module.
After fine-tuning VLMs on the PVP task, we find: 1) existing VLMs struggle to
predict precise pixel values by only fine-tuning the connection module and LLM;
and 2) prediction precision is significantly improved when the vision encoder
is also adapted. Additionally, our research reveals that incorporating pixel
value prediction as one of the VLM pre-training tasks and vision encoder
adaptation markedly boosts VLM performance on downstream image-language
understanding tasks requiring detailed image perception, such as referring
image segmentation (with an average +10.19 cIoU improvement) and video game
decision making (with average score improvements of +80.34 and +70.54 on two
games, respectively).
