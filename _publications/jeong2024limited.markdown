---
layout: publication
title: 'The Limited Impact Of Medical Adaptation Of Large Language And Vision-language Models'
authors: Daniel P. Jeong, Pranav Mani, Saurabh Garg, Zachary C. Lipton, Michael Oberst
conference: "Arxiv"
year: 2024
bibkey: jeong2024limited
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.08870'}
tags: ['Few-Shot', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
Several recent works seek to adapt general-purpose large language models
(LLMs) and vision-language models (VLMs) for medical applications through
continued pretraining on publicly available biomedical corpora. These works
typically claim that such domain-adaptive pretraining improves performance on
various downstream medical tasks, such as answering medical exam questions. In
this paper, we compare ten "medical" LLMs and two VLMs against their
corresponding base models, arriving at a different conclusion: all medical VLMs
and nearly all medical LLMs fail to consistently improve over their base models
in the zero-/few-shot prompting and supervised fine-tuning regimes for medical
question answering (QA). For instance, on clinical-note-based QA tasks in the
3-shot setting, medical LLMs outperform their base models in only 26.7% of
cases, reach a (statistical) tie in 16.7% of cases, and perform significantly
worse in the remaining 56.7% of cases. Our conclusions are based on (i)
comparing each medical model directly against its base model; (ii) optimizing
the prompts for each model separately in zero-/few-shot prompting; and (iii)
accounting for statistical uncertainty in comparisons. Our findings suggest
that state-of-the-art general-domain models may already exhibit strong medical
knowledge and reasoning capabilities, and offer recommendations to strengthen
the conclusions of future studies.
