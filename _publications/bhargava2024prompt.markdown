---
layout: publication
title: 'Prompt Baking'
authors: Aman Bhargava, Cameron Witkowski, Alexander Detkov, Matt Thomson
conference: "Arxiv"
year: 2024
bibkey: bhargava2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13697"}
tags: ['Responsible AI', 'Agentic', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Two primary ways to change LLM behavior are prompting and weight updates
(e.g., fine-tuning). Prompting LLMs is simple and effective, specifying the
desired changes explicitly in natural language, whereas weight updates provide
more expressive and permanent behavior changes, specified implicitly via
training on large datasets. We present a technique for "baking" prompts into
the weights of an LLM. Prompt Baking converts a prompt \\(u\\) and initial weights
\\(\theta\\) to a new set of weights \\(\theta_u\\) such that new "baked" LLM behaves
like the original prompted LLM. Mathematically, we minimize the KL divergence
between \\(P_\theta(\cdot | u)\\) and \\(P_\{\theta_u\}(\cdot)\\), where \\(P\\) is the LLM's
probability distribution over token sequences. Across all our experiments, we
find prompts can be readily baked into weight updates. Baking chain-of-thought
prompts improves zero-shot performance on GSM8K, ASDiv, MBPP, ARC-Easy,
ARC-Challenge, and CommonsenseQA benchmarks. Baking news headlines directly
updates an LLM's knowledge. And baking instructions & personas alleviates
"prompt forgetting" over long sequences. Furthermore, stopping baking early
creates "half-baked" models, continuously scaling prompt strength. Baked models
retain their sensitivity to further prompting and baking, including
re-prompting with the baked-in prompt. Surprisingly, the re-prompted models
yield further performance gains in instruction following, as well as math
reasoning and coding benchmarks. Taking re-prompting and re-baking to the limit
yields a form of iterative self-improvement we call Prompt Pursuit, and
preliminary results on instruction following exhibit dramatic performance
gains. Finally, we discuss implications for AI safety, continuous model
updating, enhancing real-time learning capabilities in LLM-based agents, and
generating more stable AI personas.
