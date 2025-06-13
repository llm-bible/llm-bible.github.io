---
layout: publication
title: 'Domain-specific Text Generation For Machine Translation'
authors: Yasmin Moslem, Rejwanul Haque, John D. Kelleher, Andy Way
conference: "Proceedings of the 15th biennial conference of the Association for Machine Translation in the Americas (2022) Volume 1 Research Track pages 14-30 Orlando USA. Association for Machine Translation in the Americas"
year: 2022
bibkey: moslem2022domain
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2208.05909'}
tags: ['Language Modeling', 'Transformer', 'RAG', 'Training Techniques', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
Preservation of domain knowledge from the source to target is crucial in any
translation workflow. It is common in the translation industry to receive
highly specialized projects, where there is hardly any parallel in-domain data.
In such scenarios where there is insufficient in-domain data to fine-tune
Machine Translation (MT) models, producing translations that are consistent
with the relevant context is challenging. In this work, we propose a novel
approach to domain adaptation leveraging state-of-the-art pretrained language
models (LMs) for domain-specific data augmentation for MT, simulating the
domain characteristics of either (a) a small bilingual dataset, or (b) the
monolingual source text to be translated. Combining this idea with
back-translation, we can generate huge amounts of synthetic bilingual in-domain
data for both use cases. For our investigation, we use the state-of-the-art
Transformer architecture. We employ mixed fine-tuning to train models that
significantly improve translation of in-domain texts. More specifically, in
both scenarios, our proposed methods achieve improvements of approximately 5-6
BLEU and 2-3 BLEU, respectively, on the Arabic-to-English and English-to-Arabic
language pairs. Furthermore, the outcome of human evaluation corroborates the
automatic evaluation results.
