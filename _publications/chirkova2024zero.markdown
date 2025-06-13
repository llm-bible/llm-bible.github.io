---
layout: publication
title: 'Zero-shot Cross-lingual Transfer In Instruction Tuning Of Large Language Models'
authors: Nadezhda Chirkova, Vassilina Nikoulina
conference: "Arxiv"
year: 2024
bibkey: chirkova2024zero
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.14778'}
tags: ['Prompting', 'Training Techniques']
---
Instruction tuning (IT) is widely used to teach pretrained large language
models (LLMs) to follow arbitrary instructions, but is under-studied in
multilingual settings. In this work, we conduct a systematic study of zero-shot
cross-lingual transfer in IT, when an LLM is instruction-tuned on English-only
data and then tested on user prompts in other languages. We advocate for the
importance of evaluating various aspects of model responses in multilingual
instruction following and investigate the influence of different model
configuration choices. We find that cross-lingual transfer does happen
successfully in IT even if all stages of model training are English-centric,
but only if multiliguality is taken into account in hyperparameter tuning and
with large enough IT data. English-trained LLMs are capable of generating
correct-language, comprehensive and helpful responses in other languages, but
suffer from low factuality and may occasionally have fluency errors.
