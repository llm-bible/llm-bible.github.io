---
layout: publication
title: 'Enhancing Llms For Identifying And Prioritizing Important Medical Jargons From Electronic Health Record Notes Utilizing Data Augmentation'
authors: Won Seok Jang, Sharmin Sultana, Zonghai Yao, Hieu Tran, Zhichao Yang, Sunjae Kwon, Hong Yu
conference: "Arxiv"
year: 2025
bibkey: jang2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16022"}
tags: ['Fine-Tuning', 'GPT', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
OpenNotes enables patients to access EHR notes, but medical jargon can hinder
comprehension. To improve understanding, we evaluated closed- and open-source
LLMs for extracting and prioritizing key medical terms using prompting,
fine-tuning, and data augmentation. We assessed LLMs on 106 expert-annotated
EHR notes, experimenting with (i) general vs. structured prompts, (ii)
zero-shot vs. few-shot prompting, (iii) fine-tuning, and (iv) data
augmentation. To enhance open-source models in low-resource settings, we used
ChatGPT for data augmentation and applied ranking techniques. We incrementally
increased the augmented dataset size (10 to 10,000) and conducted 5-fold
cross-validation, reporting F1 score and Mean Reciprocal Rank (MRR). Our result
show that fine-tuning and data augmentation improved performance over other
strategies. GPT-4 Turbo achieved the highest F1 (0.433), while Mistral7B with
data augmentation had the highest MRR (0.746). Open-source models, when
fine-tuned or augmented, outperformed closed-source models. Notably, the best
F1 and MRR scores did not always align. Few-shot prompting outperformed
zero-shot in vanilla models, and structured prompts yielded different
preferences across models. Fine-tuning improved zero-shot performance but
sometimes degraded few-shot performance. Data augmentation performed comparably
or better than other methods. Our evaluation highlights the effectiveness of
prompting, fine-tuning, and data augmentation in improving model performance
for medical jargon extraction in low-resource scenarios.
