---
layout: publication
title: 'Can Llms Reason Abstractly Over Math Word Problems Without Cot? Disentangling Abstract Formulation From Arithmetic Computation'
authors: Ziling Cheng, Meng Cao, Leila Pishdad, Yanshuai Cao, Jackie Chi Kit Cheung
conference: "Arxiv"
year: 2025
bibkey: cheng2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23701"}
tags: ['Uncategorized']
---
Final-answer-based metrics are commonly used for evaluating large language models (LLMs) on math word problems, often taken as proxies for reasoning ability. However, such metrics conflate two distinct sub-skills: abstract formulation (capturing mathematical relationships using expressions) and arithmetic computation (executing the calculations). Through a disentangled evaluation on GSM8K and SVAMP, we find that the final-answer accuracy of Llama-3 and Qwen2.5 (1B-32B) without CoT is overwhelmingly bottlenecked by the arithmetic computation step and not by the abstract formulation step. Contrary to the common belief, we show that CoT primarily aids in computation, with limited impact on abstract formulation. Mechanistically, we show that these two skills are composed conjunctively even in a single forward pass without any reasoning steps via an abstract-then-compute mechanism: models first capture problem abstractions, then handle computation. Causal patching confirms these abstractions are present, transferable, composable, and precede computation. These behavioural and mechanistic findings highlight the need for disentangled evaluation to accurately assess LLM reasoning and to guide future improvements.
