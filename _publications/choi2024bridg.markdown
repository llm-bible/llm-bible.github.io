---
layout: publication
title: 'Bridg MT: Enhancing Llms'' Machine Translation Capabilities With Sentence Bridging And Gradual MT'
authors: Seung-woo Choi, Ga-hyun Yoo, Jay-yoon Lee
conference: "Arxiv"
year: 2024
bibkey: choi2024bridg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11693"}
tags: ['Training Techniques', 'Few-Shot', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Recent Large Language Models (LLMs) have demonstrated impressive translation performance without requiring fine-tuning on additional parallel corpora. However, they still face significant challenges in certain scenarios, particularly when translating low-resource languages. A common approach to address this issue is to provide external knowledge, such as few-shot examples, to assist LLMs in translating specific source sentences. However, this method is fundamentally limited by the quality or quantity of relevant sources, which cannot always be guaranteed. To reduce LLMs' reliance on external sources, we propose BridG MT, a method that combines Sentence Bridging, which generates a sequence of sentences as a bridge that gradually transition from easy-to-translate to more difficult, and Gradual MT, which sequentially translates these sentences using earlier translations as few-shot examples for subsequent ones. Experiments conducted on four LLMs across seven languages demonstrate that our method effectively enhances translation performance, even outperforming translation methods that rely on a large number of few-shot examples.
