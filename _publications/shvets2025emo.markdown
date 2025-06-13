---
layout: publication
title: 'Emo Pillars: Knowledge Distillation To Support Fine-grained Context-aware And Context-less Emotion Classification'
authors: Alexander Shvets
conference: "Arxiv"
year: 2025
bibkey: shvets2025emo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.16856"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Distillation', 'GPT', 'Pretraining Methods', 'BERT', 'Fine-Tuning']
---
Most datasets for sentiment analysis lack context in which an opinion was
expressed, often crucial for emotion understanding, and are mainly limited by a
few emotion categories. Foundation large language models (LLMs) like GPT-4
suffer from over-predicting emotions and are too resource-intensive. We design
an LLM-based data synthesis pipeline and leverage a large model, Mistral-7b,
for the generation of training examples for more accessible, lightweight
BERT-type encoder models. We focus on enlarging the semantic diversity of
examples and propose grounding the generation into a corpus of narratives to
produce non-repetitive story-character-centered utterances with unique contexts
over 28 emotion classes. By running 700K inferences in 450 GPU hours, we
contribute with the dataset of 100K contextual and also 300K context-less
examples to cover both scenarios. We use it for fine-tuning pre-trained
encoders, which results in several Emo Pillars models. We show that Emo Pillars
models are highly adaptive to new domains when tuned to specific tasks such as
GoEmotions, ISEAR, IEMOCAP, and EmoContext, reaching the SOTA performance on
the first three. We also validate our dataset, conducting statistical analysis
and human evaluation, and confirm the success of our measures in utterance
diversification (although less for the neutral class) and context
personalization, while pointing out the need for improved handling of
out-of-taxonomy labels within the pipeline.
