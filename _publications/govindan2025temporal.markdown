---
layout: publication
title: 'Temporal Alignment Of Time Sensitive Facts With Activation Engineering'
authors: Sanjay Govindan, Maurice Pagnucco, Yang Song
conference: "Arxiv"
year: 2025
bibkey: govindan2025temporal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14158'}
tags: ['Fine-Tuning', 'Prompting', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) are trained on diverse and often conflicting knowledge spanning multiple domains and time periods. Some of this knowledge is only valid within specific temporal contexts, such as answering the question, "Who is the President of the United States in 2022?" Ensuring LLMs generate time appropriate responses is crucial for maintaining relevance and accuracy. In this work we explore activation engineering as a method for temporally aligning LLMs to improve factual recall without any training or dataset creation. In this research we explore an activation engineering technique to ground three versions of LLaMA 2 to specific points in time and examine the effects of varying injection layers and prompting strategies. Our experiments demonstrate up to a 44% and 16% improvement in relative and explicit prompting respectively, achieving comparable performance to the fine-tuning method proposed by Zhao et al. (2024) . Notably, our approach achieves similar results to the fine-tuning baseline while being significantly more computationally efficient and requiring no pre-aligned datasets.
