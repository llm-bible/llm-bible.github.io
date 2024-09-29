---
layout: publication
title: 'Can Github Issues Be Solved With Tree Of Thoughts?'
authors: La Rosa Ricardo, Hulse Corey, Liu Bangdi
conference: "Arxiv"
year: 2024
bibkey: larosa2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13057"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
While there have been extensive studies in code generation by large language models (LLM) where benchmarks like HumanEval have been surpassed with an impressive 96.337; success rate these benchmarks predominantly judge a models performance on basic function-level code generation and lack the critical thinking and concept of scope required of real-world scenarios such as solving GitHub issues. This research introduces the application of the Tree of Thoughts (ToT) language model reasoning framework for enhancing the decision-making and problem-solving abilities of LLMs for this complex task. Compared to traditional input-output (IO) prompting and Retrieval Augmented Generation (RAG) techniques ToT is designed to improve performance by facilitating a structured exploration of multiple reasoning trajectories and enabling self-assessment of potential solutions. We experimentally deploy ToT in tackling a Github issue contained within an instance of the SWE-bench. However our results reveal that the ToT framework alone is not enough to give LLMs the critical reasoning capabilities to outperform existing methods. In this paper we analyze the potential causes of these shortcomings and identify key areas for improvement such as deepening the thought process and introducing agentic capabilities. The insights of this research are aimed at informing future directions for refining the application of ToT and better harnessing the potential of LLMs in real-world problem-solving scenarios.
