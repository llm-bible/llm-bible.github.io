---
layout: publication
title: 'Image First Or Text First? Optimising The Sequencing Of Modalities In Large Language Model Prompting And Reasoning Tasks'
authors: Grant Wardle, Teo Susnjak
conference: "Arxiv"
year: 2024
bibkey: wardle2024image
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.03062'}
tags: ['Transformer', 'Model Architecture', 'Applications', 'Tools', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
This paper examines how the sequencing of images and text within multi-modal
prompts influences the reasoning performance of large language models (LLMs).
We performed empirical evaluations using three commercial LLMs. Our results
demonstrate that the order in which modalities are presented can significantly
affect performance, particularly in tasks of varying complexity. For simpler
tasks involving a single image, modality sequencing had a clear impact on
accuracy. However, in more complex tasks involving multiple images and
intricate reasoning steps, the effect of sequencing diminished, likely due to
the increased cognitive demands of the task. Our findings also highlight the
importance of question/prompt structure. In nested and multi-step reasoning
tasks, modality sequencing played a key role in shaping model performance.
While LLMs excelled in the initial stages of reasoning, they struggled to
re-incorporate earlier information, underscoring the challenges of multi-hop
reasoning within transformer architectures. This suggests that aligning the
sequence of modalities with the logical flow of reasoning steps is more
critical than modality order alone. These insights offer valuable implications
for improving multi-modal prompt design, with broader applications across
fields such as education, medical imaging, and cross-modal learning.
