---
layout: publication
title: 'Beyond Chains Of Thought: Benchmarking Latent-space Reasoning Abilities In Large Language Models'
authors: Thilo Hagendorff, Sarah Fabi
conference: "Arxiv"
year: 2025
bibkey: hagendorff2025beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.10615'}
tags: ['GPT', 'Model Architecture', 'Merging', 'Prompting', 'Responsible AI']
---
Large language models (LLMs) can perform reasoning computations both
internally within their latent space and externally by generating explicit
token sequences like chains of thought. Significant progress in enhancing
reasoning abilities has been made by scaling test-time compute. However,
understanding and quantifying model-internal reasoning abilities - the
inferential "leaps" models make between individual token predictions - remains
crucial. This study introduces a benchmark (n = 4,000 items) designed to
quantify model-internal reasoning in different domains. We achieve this by
having LLMs indicate the correct solution to reasoning problems not through
descriptive text, but by selecting a specific language of their initial
response token that is different from English, the benchmark language. This not
only requires models to reason beyond their context window, but also to
overrise their default tendency to respond in the same language as the prompt,
thereby posing an additional cognitive strain. We evaluate a set of 18 LLMs,
showing significant performance variations, with GPT-4.5 achieving the highest
accuracy (74.7%), outperforming models like Grok-2 (67.2%), and Llama 3.1 405B
(65.6%). Control experiments and difficulty scaling analyses suggest that while
LLMs engage in internal reasoning, we cannot rule out heuristic exploitations
under certain conditions, marking an area for future investigation. Our
experiments demonstrate that LLMs can "think" via latent-space computations,
revealing model-internal inference strategies that need further understanding,
especially regarding safety-related concerns such as covert planning,
goal-seeking, or deception emerging without explicit token traces.
