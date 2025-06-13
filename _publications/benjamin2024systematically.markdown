---
layout: publication
title: 'Systematically Analyzing Prompt Injection Vulnerabilities In Diverse LLM Architectures'
authors: Victoria Benjamin, Emily Braca, Israel Carter, Hafsa Kanchwala, Nava Khojasteh, Charly Landow, Yi Luo, Caroline Ma, Anna Magarelli, Rachel Mirin, Avery Moyer, Kayla Simpson, Amelia Skawinski, Thomas Heverin
conference: "Arxiv"
year: 2024
bibkey: benjamin2024systematically
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.23308"}
tags: ['Security', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Prompting']
---
This study systematically analyzes the vulnerability of 36 large language
models (LLMs) to various prompt injection attacks, a technique that leverages
carefully crafted prompts to elicit malicious LLM behavior. Across 144 prompt
injection tests, we observed a strong correlation between model parameters and
vulnerability, with statistical analyses, such as logistic regression and
random forest feature analysis, indicating that parameter size and architecture
significantly influence susceptibility. Results revealed that 56 percent of
tests led to successful prompt injections, emphasizing widespread vulnerability
across various parameter sizes, with clustering analysis identifying distinct
vulnerability profiles associated with specific model configurations.
Additionally, our analysis uncovered correlations between certain prompt
injection techniques, suggesting potential overlaps in vulnerabilities. These
findings underscore the urgent need for robust, multi-layered defenses in LLMs
deployed across critical infrastructure and sensitive industries. Successful
prompt injection attacks could result in severe consequences, including data
breaches, unauthorized access, or misinformation. Future research should
explore multilingual and multi-step defenses alongside adaptive mitigation
strategies to strengthen LLM security in diverse, real-world environments.
