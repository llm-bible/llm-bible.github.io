---
layout: publication
title: 'Few-shot Cross-lingual Transfer For Prompting Large Language Models In Low-resource Languages'
authors: Christopher Toukmaji
conference: "Arxiv"
year: 2024
bibkey: toukmaji2024few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.06018"}
tags: ['Training Techniques', 'Few-Shot', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications', 'In-Context Learning']
---
Large pre-trained language models (PLMs) are at the forefront of advances in
Natural Language Processing. One widespread use case of PLMs is "prompting" -
or in-context learning - where a user provides a description of a task and some
completed examples of the task to a PLM as context before prompting the PLM to
perform the task on a new example. Only the largest, most capable PLMs are able
to perform in-context learning effectively, and these models are typically
trained with a predominantly English corpus, leaving all other languages
behind. The data limitations in most languages preclude the training of
language-specific PLMs capable of prompting. Albeit the surge in work of
prompting settings, it is still unclear how PLMs should be adapted
cross-lingually specifically for prompting. We evaluate the possible methods to
adapt LLaMa, a 7B parameter open-source PLM mainly trained in English, for
prompting in low-resource languages, namely for Kinyarwanda, Hausa, and
Luganda. We consider three methods: few-shot prompting (prompt),
language-adaptive fine-tuning (LAFT), and neural machine translation
(translate), and evaluate on abstractive summarization, multi-class topic
classification, and named-entity recognition. Although LAFT carries the
greatest compute cost and intuitively should lead to the best results, our
experiments exhibit that LAFT is only occasionally the optimal choice for
adapting PLMs for prompting. Rather, the translate and prompt settings are a
compute-efficient and cost-effective method of few-shot prompting for the
selected low-resource languages. We find that the results are task and language
dependent but find that the prompting method is the best on average across all
tasks and languages. Results show that the prompt setting performs better than
both translating and LAFT with statistical significance for all shots when
aggregated across all tasks and languages.
