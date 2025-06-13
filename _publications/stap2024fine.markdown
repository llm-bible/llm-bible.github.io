---
layout: publication
title: 'The Fine-tuning Paradox: Boosting Translation Quality Without Sacrificing LLM Abilities'
authors: David Stap, Eva Hasler, Bill Byrne, Christof Monz, Ke Tran
conference: "Arxiv"
year: 2024
bibkey: stap2024fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.20089'}
tags: ['Few-Shot', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Pretraining Methods']
---
Fine-tuning large language models (LLMs) for machine translation has shown
improvements in overall translation quality. However, it is unclear what is the
impact of fine-tuning on desirable LLM behaviors that are not present in neural
machine translation models, such as steerability, inherent document-level
translation abilities, and the ability to produce less literal translations. We
perform an extensive translation evaluation on the LLaMA and Falcon family of
models with model size ranging from 7 billion up to 65 billion parameters. Our
results show that while fine-tuning improves the general translation quality of
LLMs, several abilities degrade. In particular, we observe a decline in the
ability to perform formality steering, to produce technical translations
through few-shot examples, and to perform document-level translation. On the
other hand, we observe that the model produces less literal translations after
fine-tuning on parallel data. We show that by including monolingual data as
part of the fine-tuning data we can maintain the abilities while simultaneously
enhancing overall translation quality. Our findings emphasize the need for
fine-tuning strategies that preserve the benefits of LLMs for machine
translation.
