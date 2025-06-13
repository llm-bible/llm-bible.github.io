---
layout: publication
title: 'Language Models As Black-box Optimizers For Vision-language Models'
authors: Shihong Liu, Zhiqiu Lin, Samuel Yu, Ryan Lee, Tiffany Ling, Deepak Pathak, Deva Ramanan
conference: "Arxiv"
year: 2023
bibkey: liu2023language
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.05950'}
tags: ['RAG', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Multimodal Models', 'Pretraining Methods']
---
Vision-language models (VLMs) pre-trained on web-scale datasets have
demonstrated remarkable capabilities on downstream tasks when fine-tuned with
minimal data. However, many VLMs rely on proprietary data and are not
open-source, which restricts the use of white-box approaches for fine-tuning.
As such, we aim to develop a black-box approach to optimize VLMs through
natural language prompts, thereby avoiding the need to access model parameters,
feature embeddings, or even output logits. We propose employing chat-based LLMs
to search for the best text prompt for VLMs. Specifically, we adopt an
automatic hill-climbing procedure that converges to an effective prompt by
evaluating the performance of current prompts and asking LLMs to refine them
based on textual feedback, all within a conversational process without
human-in-the-loop. In a challenging 1-shot image classification setup, our
simple approach surpasses the white-box continuous prompting method (CoOp) by
an average of 1.5% across 11 datasets including ImageNet. Our approach also
outperforms both human-engineered and LLM-generated prompts. We highlight the
advantage of conversational feedback that incorporates both positive and
negative prompts, suggesting that LLMs can utilize the implicit gradient
direction in textual feedback for a more efficient search. In addition, we find
that the text prompts generated through our strategy are not only more
interpretable but also transfer well across different VLM architectures in a
black-box manner. Lastly, we apply our framework to optimize the
state-of-the-art black-box VLM (DALL-E 3) for text-to-image generation, prompt
inversion, and personalization.
