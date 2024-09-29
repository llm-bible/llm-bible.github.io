---
layout: publication
title: 'AI Sandbagging: Language Models Can Strategically Underperform On Evaluations'
authors: Van Der Weij Teun, Hofstätter Felix, Jaffe Ollie, Brown Samuel F., Ward Francis Rhys
conference: "Arxiv"
year: 2024
bibkey: vanderweij2024ai
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07358"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Security']
---
Trustworthy capability evaluations are crucial for ensuring the safety of AI systems and are becoming a key component of AI regulation. However the developers of an AI system or the AI system itself may have incentives for evaluations to understate the AIs actual capability. These conflicting interests lead to the problem of sandbagging (unicodex2013) which we define as strategic underperformance on an evaluation. In this paper we assess sandbagging capabilities in contemporary language models (LMs). We prompt frontier LMs like GPT-4 and Claude 3 Opus to selectively underperform on dangerous capability evaluations while maintaining performance on general (harmless) capability evaluations. Moreover we find that models can be fine-tuned on a synthetic dataset to hide specific capabilities unless given a password. This behaviour generalizes to high-quality held-out benchmarks such as WMDP. In addition we show that both frontier and smaller models can be prompted or password-locked to target specific scores on a capability evaluation. Even more we found that a capable password-locked model (Llama 3 70b) is reasonably able to emulate a less capable model (Llama 2 7b). Overall our results suggest that capability evaluations are vulnerable to sandbagging. This vulnerability decreases the trustworthiness of evaluations and thereby undermines important safety decisions regarding the development and deployment of advanced AI systems.
