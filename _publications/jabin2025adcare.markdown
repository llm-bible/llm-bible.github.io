---
layout: publication
title: 'Adcare-vlm: Leveraging Large Vision Language Model (LVLM) To Monitor Long-term Medication Adherence And Care'
authors: Md Asaduzzaman Jabin, Hanqi Jiang, Yiwei Li, Patrick Kaggwa, Eugene Douglass, Juliet N. Sekandi, Tianming Liu
conference: "Arxiv"
year: 2025
bibkey: jabin2025adcare
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00275"}
tags: ['Fine-Tuning', 'Interpretability and Explainability', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Multimodal Models']
---
Chronic diseases, including diabetes, hypertension, asthma, HIV-AIDS,
epilepsy, and tuberculosis, necessitate rigorous adherence to medication to
avert disease progression, manage symptoms, and decrease mortality rates.
Adherence is frequently undermined by factors including patient behavior,
caregiver support, elevated medical costs, and insufficient healthcare
infrastructure. We propose AdCare-VLM, a specialized Video-LLaVA-based
multimodal large vision language model (LVLM) aimed at visual question
answering (VQA) concerning medication adherence through patient videos. We
employ a private dataset comprising 806 custom-annotated tuberculosis (TB)
medication monitoring videos, which have been labeled by clinical experts, to
fine-tune the model for adherence pattern detection. We present LLM-TB-VQA, a
detailed medical adherence VQA dataset that encompasses positive, negative, and
ambiguous adherence cases. Our method identifies correlations between visual
features, such as the clear visibility of the patient's face, medication, water
intake, and the act of ingestion, and their associated medical concepts in
captions. This facilitates the integration of aligned visual-linguistic
representations and improves multimodal interactions. Experimental results
indicate that our method surpasses parameter-efficient fine-tuning (PEFT)
enabled VLM models, such as LLaVA-V1.5 and Chat-UniVi, with absolute
improvements ranging from 3.1% to 3.54% across pre-trained, regular, and
low-rank adaptation (LoRA) configurations. Comprehensive ablation studies and
attention map visualizations substantiate our approach, enhancing
interpretability.
