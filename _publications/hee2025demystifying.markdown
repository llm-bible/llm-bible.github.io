---
layout: publication
title: 'Demystifying Hateful Content: Leveraging Large Multimodal Models For Hateful Meme Detection With Explainable Decisions'
authors: Ming Shan Hee, Roy Ka-wei Lee
conference: "Arxiv"
year: 2025
bibkey: hee2025demystifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11073'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Transformer', 'RAG', 'Model Architecture', 'Tools', 'Training Techniques', 'Multimodal Models', 'Pre-Training', 'Interpretability']
---
Hateful meme detection presents a significant challenge as a multimodal task
due to the complexity of interpreting implicit hate messages and contextual
cues within memes. Previous approaches have fine-tuned pre-trained
vision-language models (PT-VLMs), leveraging the knowledge they gained during
pre-training and their attention mechanisms to understand meme content.
However, the reliance of these models on implicit knowledge and complex
attention mechanisms renders their decisions difficult to explain, which is
crucial for building trust in meme classification. In this paper, we introduce
IntMeme, a novel framework that leverages Large Multimodal Models (LMMs) for
hateful meme classification with explainable decisions. IntMeme addresses the
dual challenges of improving both accuracy and explainability in meme
moderation. The framework uses LMMs to generate human-like, interpretive
analyses of memes, providing deeper insights into multimodal content and
context. Additionally, it uses independent encoding modules for both memes and
their interpretations, which are then combined to enhance classification
performance. Our approach addresses the opacity and misclassification issues
associated with PT-VLMs, optimizing the use of LMMs for hateful meme detection.
We demonstrate the effectiveness of IntMeme through comprehensive experiments
across three datasets, showcasing its superiority over state-of-the-art models.
