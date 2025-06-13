---
layout: publication
title: 'Training And Evaluating Language Models With Template-based Data Generation'
authors: Yifan Zhang
conference: "Arxiv"
year: 2024
bibkey: zhang2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.18104"}
  - {name: "Code", url: "https://huggingface.co/datasets/math-ai/TemplateGSM"}
  - {name: "Code", url: "https://github.com/iiis-ai/TemplateMath"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Pre-Training']
---
The rapid advancement of large language models (LLMs) such as GPT-3, PaLM,
and Llama has significantly transformed natural language processing, showcasing
remarkable capabilities in understanding and generating language. However,
these models often struggle with tasks requiring complex reasoning,
particularly in mathematical problem-solving, due in part to the scarcity of
large-scale, high-quality, domain-specific datasets necessary for training
sophisticated reasoning abilities. To address this limitation, we introduce
Template-based Data Generation (TDG), a novel approach that leverages LLMs
(GPT-4) to automatically generate parameterized meta-templates, which are then
used to synthesize a vast array of high-quality problems and solutions.
Leveraging TDG, we create TemplateMath Part I: TemplateGSM, a dataset
comprising over 7 million synthetically generated grade school math
problems--each accompanied by code-based and natural language solutions--with
the potential to generate an effectively unlimited number more. This dataset
alleviates the scarcity of large-scale mathematical datasets and serves as a
valuable resource for pre-training, fine-tuning, and evaluating LLMs in
mathematical reasoning. Our method not only enables the generation of virtually
infinite data but also elevates data augmentation to a new level by using GPT-4
for meta-template generation, ensuring diverse and high-quality problem
structures. The TemplateMath Part I: TemplateGSM dataset is publicly available
at https://huggingface.co/datasets/math-ai/TemplateGSM. The code is available
at https://github.com/iiis-ai/TemplateMath.
