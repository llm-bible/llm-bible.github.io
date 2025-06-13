---
layout: publication
title: 'Innate Reasoning Is Not Enough: In-context Learning Enhances Reasoning Large Language Models With Less Overthinking'
authors: Yuyao Ge, Shenghua Liu, Yiwei Wang, Lingrui Mei, Lizhe Chen, Baolong Bi, Xueqi Cheng
conference: "Arxiv"
year: 2025
bibkey: ge2025innate
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.19602'}
tags: ['Attention Mechanism', 'Few-Shot', 'Training Techniques', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'In-Context Learning']
---
Recent advances in Large Language Models (LLMs) have introduced Reasoning
Large Language Models (RLLMs), which employ extended thinking processes with
reflection and self-correction capabilities, demonstrating the effectiveness of
test-time scaling. RLLMs exhibit innate Chain-of-Thought (CoT) reasoning
capability obtained from training, leading to a natural question: "Is CoT
prompting, a popular In-Context Learning (ICL) method for chat LLMs, necessary
to enhance the reasoning capability of RLLMs?" In this work, we present the
first comprehensive analysis of the impacts of Zero-shot CoT and Few-shot CoT
on RLLMs across mathematical reasoning tasks. We examine models ranging from
1.5B to 32B parameters, finding that contrary to concerns, CoT prompting
significantly enhances RLLMs' performance in most scenarios. Our results reveal
distinct patterns: large-capacity models show minimal improvement on simple
tasks but substantial gains on complex problems, while smaller models exhibit
the opposite behavior. Further analysis demonstrates that CoT prompting
effectively controls the distribution of the numbers of thinking tokens and
reasoning steps, reducing excessive reflections by approximately 90% in some
cases. Moreover, attention logits analysis reveals the RLLMs' overfitting to
reflection-related words, which is mitigated by external CoT guidance. Notably,
our experiments indicate that for RLLMs, one-shot CoT consistently yields
superior performance compared to Few-shot CoT approaches. Our findings provide
important insights for optimizing RLLMs' performance through appropriate
prompting strategies.
