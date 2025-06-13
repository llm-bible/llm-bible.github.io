---
layout: publication
title: 'Llms-in-the-loop Part-1: Expert Small AI Models For Bio-medical Text Translation'
authors: Bunyamin Keles, Murat Gunay, Serdar I. Caglar
conference: "Arxiv"
year: 2024
bibkey: keles2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12126"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Applications']
---
Machine translation is indispensable in healthcare for enabling the global
dissemination of medical knowledge across languages. However, complex medical
terminology poses unique challenges to achieving adequate translation quality
and accuracy. This study introduces a novel "LLMs-in-the-loop" approach to
develop supervised neural machine translation models optimized specifically for
medical texts. While large language models (LLMs) have demonstrated powerful
capabilities, this research shows that small, specialized models trained on
high-quality in-domain (mostly synthetic) data can outperform even vastly
larger LLMs.
  Custom parallel corpora in six languages were compiled from scientific
articles, synthetically generated clinical documents, and medical texts. Our
LLMs-in-the-loop methodology employs synthetic data generation, rigorous
evaluation, and agent orchestration to enhance performance. We developed small
medical translation models using the MarianMT base model. We introduce a new
medical translation test dataset to standardize evaluation in this domain.
Assessed using BLEU, METEOR, ROUGE, and BERT scores on this test set, our
MarianMT-based models outperform Google Translate, DeepL, and GPT-4-Turbo.
  Results demonstrate that our LLMs-in-the-loop approach, combined with
fine-tuning high-quality, domain-specific data, enables specialized models to
outperform general-purpose and some larger systems. This research, part of a
broader series on expert small models, paves the way for future
healthcare-related AI developments, including deidentification and bio-medical
entity extraction models. Our study underscores the potential of tailored
neural translation models and the LLMs-in-the-loop methodology to advance the
field through improved data generation, evaluation, agent, and modeling
techniques.
