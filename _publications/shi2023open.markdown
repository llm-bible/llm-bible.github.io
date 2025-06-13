---
layout: publication
title: 'Sotana: The Open-source Software Development Assistant'
authors: Ensheng Shi, Fengji Zhang, Yanlin Wang, Bei Chen, Lun Du, Hongyu Zhang, Shi Han, Dongmei Zhang, Hongbin Sun
conference: "Arxiv"
year: 2023
bibkey: shi2023open
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.13416'}
  - {name: "Code", url: 'https://github.com/DeepSoftwareAnalytics/SoTaNa'}
tags: ['Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
Software development plays a crucial role in driving innovation and
efficiency across modern societies. To meet the demands of this dynamic field,
there is a growing need for an effective software development assistant.
However, existing large language models represented by ChatGPT suffer from
limited accessibility, including training data and model weights. Although
other large open-source models like LLaMA have shown promise, they still
struggle with understanding human intent. In this paper, we present SoTaNa, an
open-source software development assistant. SoTaNa utilizes ChatGPT to generate
high-quality instruction-based data for the domain of software engineering and
employs a parameter-efficient fine-tuning approach to enhance the open-source
foundation model, LLaMA. We evaluate the effectiveness of \our\{\} in answering
Stack Overflow questions and demonstrate its capabilities. Additionally, we
discuss its capabilities in code summarization and generation, as well as the
impact of varying the volume of generated data on model performance. Notably,
SoTaNa can run on a single GPU, making it accessible to a broader range of
researchers. Our code, model weights, and data are public at
\url\{https://github.com/DeepSoftwareAnalytics/SoTaNa\}.
