---
layout: publication
title: 'Exploring Small Language Models With Prompt-learning Paradigm For Efficient Domain-specific Text Classification'
authors: Luo Hengyu, Liu Peng, Esping Stefan
conference: "Arxiv"
year: 2023
bibkey: luo2023exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.14779"}
tags: ['Agentic', 'Efficiency And Optimization', 'Few Shot', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
'Domain-specific text classification faces the challenge of scarce labeled data due to the high cost of manual labeling. Prompt-learning, known for its efficiency in few-shot scenarios, is proposed as an alternative to traditional fine-tuning methods. And besides, although large language models (LLMs) have gained prominence, small language models (SLMs, with under 1B parameters) offer significant customizability, adaptability, and cost-effectiveness for domain-specific tasks, given industry constraints. In this study, we investigate the potential of SLMs combined with prompt-learning paradigm for domain-specific text classification, specifically within customer-agent interactions in retail. Our evaluations show that, in few-shot settings when prompt-based model fine-tuning is possible, T5-base, a typical SLM with 220M parameters, achieve approximately 75&#37; accuracy with limited labeled data (up to 15&#37; of full data), which shows great potentials of SLMs with prompt-learning. Based on this, We further validate the effectiveness of active few-shot sampling and the ensemble strategy in the prompt-learning pipeline that contribute to a remarkable performance gain. Besides, in zero-shot settings with a fixed model, we underscore a pivotal observation that, although the GPT-3.5-turbo equipped with around 154B parameters garners an accuracy of 55.16&#37;, the power of well designed prompts becomes evident when the FLAN-T5-large, a model with a mere 0.5&#37; of GPT-3.5-turbo''s parameters, achieves an accuracy exceeding 31&#37; with the optimized prompt, a leap from its sub-18&#37; performance with an unoptimized one. Our findings underscore the promise of prompt-learning in classification tasks with SLMs, emphasizing the benefits of active few-shot sampling, and ensemble strategies in few-shot settings, and the importance of prompt engineering in zero-shot settings.'
