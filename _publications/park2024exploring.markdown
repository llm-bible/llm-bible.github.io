---
layout: publication
title: 'M4CXR: Exploring Multi-task Potentials Of Multi-modal Large Language Models For Chest X-ray Interpretation'
authors: Park Jonggwon, Kim Soobum, Yoon Byungmu, Hyun Jihun, Choi Kyoyun
conference: "Arxiv"
year: 2024
bibkey: park2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16213"}
tags: ['Prompting', 'Reinforcement Learning', 'Tools', 'Uncategorized']
---
The rapid evolution of artificial intelligence, especially in large language
models (LLMs), has significantly impacted various domains, including
healthcare. In chest X-ray (CXR) analysis, previous studies have employed LLMs,
but with limitations: either underutilizing the multi-tasking capabilities of
LLMs or lacking clinical accuracy. This paper presents M4CXR, a multi-modal LLM
designed to enhance CXR interpretation. The model is trained on a visual
instruction-following dataset that integrates various task-specific datasets in
a conversational format. As a result, the model supports multiple tasks such as
medical report generation (MRG), visual grounding, and visual question
answering (VQA). M4CXR achieves state-of-the-art clinical accuracy in MRG by
employing a chain-of-thought prompting strategy, in which it identifies
findings in CXR images and subsequently generates corresponding reports. The
model is adaptable to various MRG scenarios depending on the available inputs,
such as single-image, multi-image, and multi-study contexts. In addition to
MRG, M4CXR performs visual grounding at a level comparable to specialized
models and also demonstrates outstanding performance in VQA. Both quantitative
and qualitative assessments reveal M4CXR's versatility in MRG, visual
grounding, and VQA, while consistently maintaining clinical accuracy.
