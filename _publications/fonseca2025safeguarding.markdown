---
layout: publication
title: 'Safeguarding Large Language Models In Real-time With Tunable Safety-performance Trade-offs'
authors: Joao Fonseca, Andrew Bell, Julia Stoyanovich
conference: "Arxiv"
year: 2025
bibkey: fonseca2025safeguarding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.02018"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Model Architecture', 'Tools', 'Language Modeling', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Applications']
---
Large Language Models (LLMs) have been shown to be susceptible to jailbreak
attacks, or adversarial attacks used to illicit high risk behavior from a
model. Jailbreaks have been exploited by cybercriminals and blackhat actors to
cause significant harm, highlighting the critical need to safeguard
widely-deployed models. Safeguarding approaches, which include fine-tuning
models or having LLMs "self-reflect", may lengthen the inference time of a
model, incur a computational penalty, reduce the semantic fluency of an output,
and restrict ``normal'' model behavior. Importantly, these Safety-Performance
Trade-offs (SPTs) remain an understudied area. In this work, we introduce a
novel safeguard, called SafeNudge, that combines Controlled Text Generation
with "nudging", or using text interventions to change the behavior of a model.
SafeNudge triggers during text-generation while a jailbreak attack is being
executed, and can reduce successful jailbreak attempts by 30% by guiding the
LLM towards a safe responses. It adds minimal latency to inference and has a
negligible impact on the semantic fluency of outputs. Further, we allow for
tunable SPTs. SafeNudge is open-source and available through https://pypi.org/,
and is compatible with models loaded with the Hugging Face "transformers"
library.
