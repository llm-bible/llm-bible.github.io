---
layout: publication
title: 'Multi-agent LLM Judge: Automatic Personalized LLM Judge Design For Evaluating Natural Language Generation Applications'
authors: Hongliu Cao, Ilias Driouich, Robin Singh, Eoin Thomas
conference: "Arxiv"
year: 2025
bibkey: cao2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02867"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning', 'RAG', 'Language Modeling', 'Ethics and Bias', 'Prompting', 'Applications']
---
Large Language Models (LLMs) have demonstrated impressive performance across
diverse domains, yet they still encounter challenges such as insufficient
domain-specific knowledge, biases, and hallucinations. This underscores the
need for robust evaluation methodologies to accurately assess LLM-based
applications. Traditional evaluation methods, which rely on word overlap or
text embeddings, are inadequate for capturing the nuanced semantic information
necessary to evaluate dynamic, open-ended text generation. Recent research has
explored leveraging LLMs to mimic human reasoning and decision-making processes
for evaluation purposes known as LLM-as-a-judge framework. However, these
existing frameworks have two significant limitations. First, they lack the
flexibility to adapt to different text styles, including various answer and
ground truth styles, thereby reducing their generalization performance. Second,
the evaluation scores produced by these frameworks are often skewed and hard to
interpret, showing a low correlation with human judgment. To address these
challenges, we propose a novel dynamic multi-agent system that automatically
designs personalized LLM judges for various natural language generation
applications. This system iteratively refines evaluation prompts and balances
the trade-off between the adaptive requirements of downstream tasks and the
alignment with human perception. Our experimental results show that the
proposed multi-agent LLM Judge framework not only enhances evaluation accuracy
compared to existing methods but also produces evaluation scores that better
align with human perception.
