---
layout: publication
title: 'Shs-nlp At Radsum23: Domain-adaptive Pre-training Of Instruction-tuned Llms For Radiology Report Impression Generation'
authors: Sanjeev Kumar Karn, Rikhiya Ghosh, Kusuma P, Oladimeji Farri
conference: "BioNLP 2023 Co-located with ACL 2023"
year: 2023
bibkey: karn2023shs
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.03264"}
tags: ['Pre-Training', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Instruction-tuned generative Large language models (LLMs) like ChatGPT and
Bloomz possess excellent generalization abilities, but they face limitations in
understanding radiology reports, particularly in the task of generating the
IMPRESSIONS section from the FINDINGS section. They tend to generate either
verbose or incomplete IMPRESSIONS, mainly due to insufficient exposure to
medical text data during training. We present a system which leverages
large-scale medical text data for domain-adaptive pre-training of
instruction-tuned LLMs to enhance its medical knowledge and performance on
specific medical tasks. We show that this system performs better in a zero-shot
setting than a number of pretrain-and-finetune adaptation methods on the
IMPRESSIONS generation task, and ranks 1st among participating systems in Task
1B: Radiology Report Summarization at the BioNLP 2023 workshop.
