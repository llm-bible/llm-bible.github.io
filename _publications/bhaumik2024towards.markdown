---
layout: publication
title: 'Towards A Generative Approach For Emotion Detection And Reasoning'
authors: Ankita Bhaumik, Tomek Strzalkowski
conference: "Arxiv"
year: 2024
bibkey: bhaumik2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.04906"}
tags: ['Fine-Tuning', 'Applications', 'Interpretability and Explainability', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large language models (LLMs) have demonstrated impressive performance in
mathematical and commonsense reasoning tasks using chain-of-thought (CoT)
prompting techniques. But can they perform emotional reasoning by concatenating
`Let's think step-by-step' to the input prompt? In this paper we investigate
this question along with introducing a novel approach to zero-shot emotion
detection and emotional reasoning using LLMs. Existing state of the art
zero-shot approaches rely on textual entailment models to choose the most
appropriate emotion label for an input text. We argue that this strongly
restricts the model to a fixed set of labels which may not be suitable or
sufficient for many applications where emotion analysis is required. Instead,
we propose framing the problem of emotion analysis as a generative
question-answering (QA) task. Our approach uses a two step methodology of
generating relevant context or background knowledge to answer the emotion
detection question step-by-step. Our paper is the first work on using a
generative approach to jointly address the tasks of emotion detection and
emotional reasoning for texts. We evaluate our approach on two popular emotion
detection datasets and also release the fine-grained emotion labels and
explanations for further training and fine-tuning of emotional reasoning
systems.
