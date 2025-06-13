---
layout: publication
title: 'RLTHF: Targeted Human Feedback For LLM Alignment'
authors: Yifei Xu, Tusher Chakraborty, Emre Kıcıman, Bibek Aryal, Eduardo Rodrigues, Srinagesh Sharma, Roberto Estevao, Maria Angels De Luis Balaguer, Jessica Wolk, Rafael Padilha, Leonardo Nunes, Shobana Balakrishnan, Songwu Lu, Ranveer Chandra
conference: "Arxiv"
year: 2025
bibkey: xu2025targeted
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13417"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Fine-tuning large language models (LLMs) to align with user preferences is
challenging due to the high cost of quality human annotations in Reinforcement
Learning from Human Feedback (RLHF) and the generalizability limitations of AI
Feedback. To address these challenges, we propose RLTHF, a human-AI hybrid
framework that combines LLM-based initial alignment with selective human
annotations to achieve full-human annotation alignment with minimal effort.
RLTHF identifies hard-to-annotate samples mislabeled by LLMs using a reward
model's reward distribution and iteratively enhances alignment by integrating
strategic human corrections while leveraging LLM's correctly labeled samples.
Evaluations on HH-RLHF and TL;DR datasets show that RLTHF reaches full-human
annotation-level alignment with only 6-7% of the human annotation effort.
Furthermore, models trained on RLTHF's curated datasets for downstream tasks
outperform those trained on fully human-annotated datasets, underscoring the
effectiveness of RLTHF's strategic data curation.
