---
layout: publication
title: 'Large Language Models Prompting With Episodic Memory'
authors: Dai Do, Quan Tran, Svetha Venkatesh, Hung Le
conference: "Arxiv"
year: 2024
bibkey: do2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.07465"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Few-Shot', 'Reinforcement Learning', 'Prompting']
---
Prompt optimization is essential for enhancing the performance of Large
Language Models (LLMs) in a range of Natural Language Processing (NLP) tasks,
particularly in scenarios of few-shot learning where training examples are
incorporated directly into the prompt. Despite the growing interest in
optimizing prompts with few-shot examples, existing methods for prompt
optimization are often resource-intensive or perform inadequately. In this
work, we propose PrOmpting with Episodic Memory (POEM), a novel prompt
optimization technique that is simple, efficient, and demonstrates strong
generalization capabilities. We approach prompt optimization as a Reinforcement
Learning (RL) challenge, using episodic memory to archive combinations of input
data, permutations of few-shot examples, and the rewards observed during
training. In the testing phase, we optimize the sequence of examples for each
test query by selecting the sequence that yields the highest total rewards from
the top-k most similar training examples in the episodic memory. Our results
show that POEM outperforms recent techniques like TEMPERA and RLPrompt by over
5.3% in various text classification tasks. Furthermore, our approach adapts
well to broader language understanding tasks, consistently outperforming
conventional heuristic methods for ordering examples.
