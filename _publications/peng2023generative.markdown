---
layout: publication
title: 'Generative Large Language Models Are All-purpose Text Analytics Engines: Text-to-text Learning Is All Your Need'
authors: Peng Cheng, Yang Xi, Chen Aokun, Yu Zehao, Smith Kaleb E, Costa Anthony B, Flores Mona G, Bian Jiang, Wu Yonghui
conference: "Arxiv"
year: 2023
bibkey: peng2023generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.06099"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
"Objective To solve major clinical natural language processing (NLP) tasks using a unified text-to-text learning architecture based on a generative large language model (LLM) via prompt tuning. Methods We formulated 7 key clinical NLP tasks as text-to-text learning and solved them using one unified generative clinical LLM, GatorTronGPT, developed using GPT-3 architecture and trained with up to 20 billion parameters. We adopted soft prompts (i.e., trainable vectors) with frozen LLM, where the LLM parameters were not updated (i.e., frozen) and only the vectors of soft prompts were updated, known as prompt tuning. We added additional soft prompts as a prefix to the input layer, which were optimized during the prompt tuning. We evaluated the proposed method using 7 clinical NLP tasks and compared them with previous task-specific solutions based on Transformer models. Results and Conclusion The proposed approach achieved state-of-the-art performance for 5 out of 7 major clinical NLP tasks using one unified generative LLM. Our approach outperformed previous task-specific transformer models by ~3&#37; for concept extraction and 7&#37; for relation extraction applied to social determinants of health, 3.4&#37; for clinical concept normalization, 3.4~10&#37; for clinical abbreviation disambiguation, and 5.5~9&#37; for natural language inference. Our approach also outperformed a previously developed prompt-based machine reading comprehension (MRC) model, GatorTron-MRC, for clinical concept and relation extraction. The proposed approach can deliver the one model for all promise from training to deployment using a unified generative LLM."
