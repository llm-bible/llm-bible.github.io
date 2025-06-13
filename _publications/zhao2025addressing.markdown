---
layout: publication
title: 'Addressing Overprescribing Challenges: Fine-tuning Large Language Models For Medication Recommendation Tasks'
authors: Zihao Zhao, Chenxiao Fan, Chongming Gao, Fuli Feng, Xiangnan He
conference: "Arxiv"
year: 2025
bibkey: zhao2025addressing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.03687'}
tags: ['Attention Mechanism', 'RAG', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Medication recommendation systems have garnered attention within healthcare
for their potential to deliver personalized and efficacious drug combinations
based on patient's clinical data. However, existing methodologies encounter
challenges in adapting to diverse Electronic Health Records (EHR) systems and
effectively utilizing unstructured data, resulting in limited generalization
capabilities and suboptimal performance. Recently, interest is growing in
harnessing Large Language Models (LLMs) in the medical domain to support
healthcare professionals and enhance patient care. Despite the emergence of
medical LLMs and their promising results in tasks like medical question
answering, their practical applicability in clinical settings, particularly in
medication recommendation, often remains underexplored.
  In this study, we evaluate both general-purpose and medical-specific LLMs for
medication recommendation tasks. Our findings reveal that LLMs frequently
encounter the challenge of overprescribing, leading to heightened clinical
risks and diminished medication recommendation accuracy. To address this issue,
we propose Language-Assisted Medication Recommendation (LAMO), which employs a
parameter-efficient fine-tuning approach to tailor open-source LLMs for optimal
performance in medication recommendation scenarios. LAMO leverages the wealth
of clinical information within clinical notes, a resource often underutilized
in traditional methodologies. As a result of our approach, LAMO outperforms
previous state-of-the-art methods by over 10% in internal validation accuracy.
Furthermore, temporal and external validations demonstrate LAMO's robust
generalization capabilities across various temporal and hospital contexts.
Additionally, an out-of-distribution medication recommendation experiment
demonstrates LAMO's remarkable accuracy even with medications outside the
training data.
