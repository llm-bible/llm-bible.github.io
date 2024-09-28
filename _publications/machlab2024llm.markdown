---
layout: publication
title: LLM In-Context Recall is Prompt Dependent
authors: Machlab Daniel, Battle Rick
conference: "Arxiv"
year: 2024
bibkey: machlab2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08865"}
tags: ['ARXIV', 'Applications', 'Ethics And Bias', 'Fine Tuning', 'LLM', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning']
---
The proliferation of Large Language Models (LLMs) highlights the critical importance of conducting thorough evaluations to discern their comparative advantages limitations and optimal use cases. Particularly important is assessing their capacity to accurately retrieve information included in a given prompt. A models ability to do this significantly influences how effectively it can utilize contextual details thus impacting its practical efficacy and dependability in real-world applications. Our research analyzes the in-context recall performance of various LLMs using the needle-in-a-haystack method. In this approach a factoid (the needle) is embedded within a block of filler text (the haystack) which the model is asked to retrieve. We assess the recall performance of each model across various haystack lengths and with varying needle placements to identify performance patterns. This study demonstrates that an LLMs recall capability is not only contingent upon the prompts content but also may be compromised by biases in its training data. Conversely adjustments to model architecture training strategy or fine-tuning can improve performance. Our analysis provides insight into LLM behavior offering direction for the development of more effective applications of LLMs.
