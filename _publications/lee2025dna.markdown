---
layout: publication
title: 'DNA 1.0 Technical Report'
authors: Jungyup Lee, Jemin Kim, Sang Park, Seungjae Lee
conference: "Arxiv"
year: 2025
bibkey: lee2025dna
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.10648"}
  - {name: "Code", url: "https://huggingface.co/dnotitia/Llama-DNA-1.0-8B-Instruct"}
  - {name: "Code", url: "https://www.dnotitia.com/contact/post-form"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Language Modeling', 'Distillation', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Pre-Training']
---
In this report, we present DNA 1.0 8B Instruct, a state-of-the-art bilingual
language model optimized for Korean and English language tasks. By applying
continual pre-training (CPT) with high-quality Korean datasets to Llama 3.1 8B
and subsequent supervised fine-tuning (SFT), we create an instruction-following
model with enhanced Korean language capabilities. This model is then merged
with Llama 3.1 8B Instruct via spherical linear interpolation (SLERP) and
undergoes further optimization through direct preference optimization (DPO) and
knowledge distillation (KD). DNA 1.0 8B Instruct achieves state-of-the-art
results on Korean-specific tasks, including KMMLU (53.26%), KoBEST (83.40%),
and BELEBELE (57.99%), while maintaining strong English capabilities on MMLU
(66.64%), MMLU-Pro (43.05%) and GSM8K (80.52%). As an open model, DNA 1.0 8B
Instruct represents a significant advancement in bilingual language modeling.
  As an open model, DNA 1.0 8B Instruct is freely available through
https://huggingface.co/dnotitia/Llama-DNA-1.0-8B-Instruct . For commercial
licensing inquiries or feedback, please contact us at
https://www.dnotitia.com/contact/post-form
