---
layout: publication
title: 'Fine-tuning Large Language Models With Human-inspired Learning Strategies In Medical Question Answering'
authors: Yang Yushi, Bean Andrew M., Mccraith Robert, Mahdi Adam
conference: "Arxiv"
year: 2024
bibkey: yang2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.07888"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Training Large Language Models (LLMs) incurs substantial data-related costs motivating the development of data-efficient training methods through optimised data ordering and selection. Human-inspired learning strategies such as curriculum learning offer possibilities for efficient training by organising data according to common human learning practices. Despite evidence that fine-tuning with curriculum learning improves the performance of LLMs for natural language understanding tasks its effectiveness is typically assessed using a single model. In this work we extend previous research by evaluating both curriculum-based and non-curriculum-based learning strategies across multiple LLMs using human-defined and automated data labels for medical question answering. Our results indicate a moderate impact of using human-inspired learning strategies for fine-tuning LLMs with maximum accuracy gains of 1.7737; per model and 1.8137; per dataset. Crucially we demonstrate that the effectiveness of these strategies varies significantly across different model-dataset combinations emphasising that the benefits of a specific human-inspired strategy for fine-tuning LLMs do not generalise. Additionally we find evidence that curriculum learning using LLM-defined question difficulty outperforms human-defined difficulty highlighting the potential of using model-generated measures for optimal curriculum design.
