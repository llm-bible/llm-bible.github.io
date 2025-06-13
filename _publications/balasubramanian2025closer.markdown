---
layout: publication
title: 'A Closer Look At Bias And Chain-of-thought Faithfulness Of Large (vision) Language Models'
authors: Sriram Balasubramanian, Samyadeep Basu, Soheil Feizi
conference: "Arxiv"
year: 2025
bibkey: balasubramanian2025closer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23945"}
tags: ['Ethics and Bias', 'Multimodal Models', 'Survey Paper', 'Tools']
---
Chain-of-thought (CoT) reasoning enhances performance of large language models, but questions remain about whether these reasoning traces faithfully reflect the internal processes of the model. We present the first comprehensive study of CoT faithfulness in large vision-language models (LVLMs), investigating how both text-based and previously unexplored image-based biases affect reasoning and bias articulation. Our work introduces a novel, fine-grained evaluation pipeline for categorizing bias articulation patterns, enabling significantly more precise analysis of CoT reasoning than previous methods. This framework reveals critical distinctions in how models process and respond to different types of biases, providing new insights into LVLM CoT faithfulness. Our findings reveal that subtle image-based biases are rarely articulated compared to explicit text-based ones, even in models specialized for reasoning. Additionally, many models exhibit a previously unidentified phenomenon we term ``inconsistent'' reasoning - correctly reasoning before abruptly changing answers, serving as a potential canary for detecting biased reasoning from unfaithful CoTs. We then apply the same evaluation pipeline to revisit CoT faithfulness in LLMs across various levels of implicit cues. Our findings reveal that current language-only reasoning models continue to struggle with articulating cues that are not overtly stated.
